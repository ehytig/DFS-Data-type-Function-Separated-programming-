# Math-code
This repository record the basic concept of Math-Function programming
# Basic
The intuition of Math-code comes from math function, look, there's a function below
$$
f(x)
$$
it has two part $f()$ and $x$, actually in math $f()$ is function but in code language like C the function should be $f(x)$, because when we define a function we also have to claim the type of $x$, so the function can't be separated from the data type.<!--so you have to write different functions for different types.-->

Now considering making a difference. First let review some math <!--knowledge-->.

Starting with the most simple function +, and we will use $sum$ to express it which will make it look like a function in your code. For the real number $x$, we can simply see sum is just
$$
sum(x_1,x_2)=x_1+x_2
$$
this sounds stupid because it‘s very clearly, but let consider $x$ to be a $2\times1$ matrix, so
$$
sum(x_1,x_2)=
\left(
\begin{array}{cc}
a_1\\
b_1
\end{array}
\right)
+
\left(
\begin{array}{cc}
a_2\\
b_2
\end{array}
\right)
=
\left(
\begin{array}{cc}
a_1+a_2\\
b_1+b_2
\end{array}
\right)
$$
That looks like different, but ponder for a while you will find the structure of sum is not changed, that maybe hard to understand, but I just want to show you a abstract function can take different forms for different variables, or data type in programming.

So there's an addition for real number and another for matrix, but we all call it addition because there have the same structure, or in math we say the obey the same rule. And it explicit form is only determined by data type.

So now if we want to design a coding language similar to this, Using compare function for example which is different for real number and complex number, try

```
define compare(x_1,x_2)

struct real{
com
}
```

<!--define sum(u1,u2) #here we define a abstract function--> 

<!--struct real-->
<!--{-->
<!--addition:-->

<!--}-->

