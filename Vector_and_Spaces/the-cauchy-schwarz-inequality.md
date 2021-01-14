# The cauchy schwarz inequality

$x,y\in \mathbb{R}^n\;|\;x,y\;\text{is non zero}$  

$$
\left\{\begin{array}{lr}
|x\cdot y|\le ||x||\,||y|| \\
|x\cdot y|=||x||\,||y||\iff x=cy\;|\;c\;\text{is}\;scalar
\end{array}\right\}\text{Cauchy Schwarz Inequality}
$$  

$p(t) = ||ty - x||^2\;|\;t\;\text{is}\;scalar$  

$||v||=\sqrt{\sum v_i} \ge 0$  

$$
\begin{aligned}
p(t) &= ||ty - x||^2 \ge 0\;|\;t\;\text{is}\; scalar\\
&=(ty-x)\cdot (ty-x)\\
&=ty\cdot ty-x\cdot ty-ty\cdot x +x \cdot x\\
&=(y\cdot y)t^2-2(x\cdot y)t+x\cdot x \ge 0\\
\end{aligned}
$$

Let $a=y\cdot y, b=2(x\cdot y), c=x\cdot x$

$$
\begin{aligned}
p\left(\frac{b}{2a}\right) &= a\frac{b^2}{4a^2}-b\frac{b}{2a}+c \ge 0\\
&=\frac{b^2}{4a}-\frac{2b^2}{4a}+c \ge 0
\end{aligned}
$$  

So, $4ac\ge b^2$  

now, back substitution  

$4(||y||^2||x||^2)\ge 4(x\cdot y)(x\cdot y)$  

$\therefore ||y||\,||x||\ge |x\cdot y|$ (cauchy schwarz inequality)