Here is the output plot for part (b) of the question

<img src="https://github.com/zyxue/stanford-cs229/blob/master/Problem-set-4/6-reinforcement-learning-the-inverted-pendulum/output.png?raw=true"/>

Compared to the answer to the same question from
[AlmostFree](http://blog.csdn.net/u013508213/article/details/53692077#reinforcement-learning-the-inverted-pendulum),
plotted with the MATLAB version of the code,

<img src="http://img.blog.csdn.net/20161230131910958"/>

my converged number of steps to failure is lower, but with less variance. I
tried to figure out why, but not conclusive. It could be due to difference in
implmentation of the cartpole model between the Python and MATLAB versions, or
my value iteration isn't implemented correctly. If you find out either case is
true, please let me know.

