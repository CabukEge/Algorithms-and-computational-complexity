## Task
**We consider the so-called partition problem:** Given are natural numbers <img src="https://render.githubusercontent.com/render/math?math=a_1, . . . ,a_n">. We want to decide whether there is an index set <img src="https://render.githubusercontent.com/render/math?math=I  \sqsubseteq\{1, . . . , n\}"> so that

<img src="https://render.githubusercontent.com/render/math?math=\sum_{i\in I}a_i = \sum_{i\in \{1,...,n\}\backslash I}a_i"> exists.



I am using dynamic programming to solve the partition problem in <img src="https://render.githubusercontent.com/render/math?math=O(nS)">. 

Consider that <img src="https://render.githubusercontent.com/render/math?math=S=\sum_{i=1}^{n}a_n">.

My solution indicates if there is such a set.

**NOTE**:
My tutor said that line 26 is always 0, I have a different opinion. I haven't had time to print the table into the terminal to be able to determine it reliably.
