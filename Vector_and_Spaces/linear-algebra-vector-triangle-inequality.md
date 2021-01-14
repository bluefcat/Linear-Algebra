# Linear algebra vector triangle inequality

## Cauchy schwarz inequality  
$x,y\in \mathbb{R}^n\;|\;x,y\;\text{is non-zero}$
$|x\cdot y|\le ||x||\,||y||$  

## Triangle inequality  
$$
\begin{aligned}
||x+y||^2&=(x+y)\cdot (x+y)  \\
&=x\cdot (x+y)+y\cdot (x+y) \\
&=x\cdot x+x\cdot y+y\cdot x+y\cdot y\\
&=||x||^2+||y||^2+2(x\cdot y)
\end{aligned}
$$
$x\cdot y\le|x\cdot y|$, $x\cdot y$ could be negative or positive.  
if $x\cdot y$ is positive, equal to $|x\cdot y|$  
$$
\begin{aligned}
||x+y||^2&=||x||^2+||y||^2+2(x\cdot y)\\
&\le ||x||^2+||y||^2 + 2||x||\,||y||\\
&\le (||x||+||y||)^2
\end{aligned}
$$
$\therefore ||x+y||\le ||x||+||y||$ (triangle inequality)