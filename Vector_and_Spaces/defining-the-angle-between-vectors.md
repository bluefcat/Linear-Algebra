# Defining the angle between vectors

$||a||$ = length  
length is scalar
  
## "Angle" between vectors
$a, b\in \mathbb{R}^n$ and $a, b$ is non zero  

reasons why I coudn't constructure  
$||b|| \gt ||a|| + ||a - b||$  
$||a|| \gt ||b|| + ||a - b||$  
$||a - b|| \gt ||a|| + ||b||$  

$\because ||x+y||\le ||x||+||y||$ (triangle inequality)  

### Low of Cosine
$c^2 + a^2 + b^2-2ab\cos{\theta}$  

$\implies||a-b||^2 = ||b||^2+||a||^2-||b||\,||a||\cos{\theta}$  

$\begin{aligned}\implies(a-b)\cdot (a-b)&=a\cdot a - a\cdot b-b\cdot a+b\cdot b\\&=||a||^2 -2(a\cdot b)+||b||^2\end{aligned}$  

$\therefore \frac{(a\cdot b)}{||a||\,||b||}=\cos{\theta}$  

(not define in zero vector situation)

## Defination of perpendicular
$\theta$ between them is $90^\circ$  

if angle between 90 degree. this mean  
$a\cdot b =||a||\,||b||\cos{90^\circ} = 0$  
$a, b$ is perpendicular $\implies a\cdot b = 0$  
we call theme $a, b$ **orthogonal**  

but zero vector dot anything, always zero. So, zero vector is **orthogonal**  to everything else even if itself.