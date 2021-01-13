# Subspace basis
## Basis
subspace $V = \{\text{span}(v_1, v_2, \cdots v_n)\;|\;v_i\in\mathbb{N}\}$ and $\{v_1,v_2,\cdots v_n\}$ is linearly independent ($\sum c_iv_i = 0 \iff c_1=c_2=\cdots c_n = 0$)  

$S=\{v_1, v_2, \cdots v_n\}$ is a basis for $V$

- span of vectors can construct $V$
  
- linearly independent 

So, $T=\{\{v_1, v_2, \cdots, v_n, v_s\}\;|\;v_s = v_1 + v_2\}$ is  linearly dependent but span $V$  

$T$ is not a basis for $V$

> Basis is **Minimum** set of vectors that spans the subspace

## Example
$S=\left\{\begin{bmatrix}2\\3\end{bmatrix}, \begin{bmatrix}7\\0\end{bmatrix}\right\}$
- what span vectors in $S$ ?  
$\text{span}(S)=\mathbb{R}^2$

- Is $S$'s vectors linearly independent ?  
$c_1\begin{bmatrix}2\\3\end{bmatrix} + c_2\begin{bmatrix}7\\0\end{bmatrix} = \begin{bmatrix}0\\0\end{bmatrix}\implies c_1=c_2=0$

$\therefore S$ is a basis for $\mathbb{R}^2$
<br></br>
$T=\left\{\begin{bmatrix}1\\0\end{bmatrix}, \begin{bmatrix}0\\1\end{bmatrix}\right\}$
- what span vectors in $T$ ?  
$\text{span}(T)=\mathbb{R}^2$

- Is $S$'s vectors linearly independent ?  
$c_1\begin{bmatrix}1\\0\end{bmatrix} + c_2\begin{bmatrix}0\\1\end{bmatrix} = \begin{bmatrix}0\\0\end{bmatrix}\implies c_1=c_2=0$

$\therefore T$ is a basis for $\mathbb{R}^2$ (called **standard basis**)

They Can have multiple basis

---

$\{v_1, v_2, \cdots v_n\}$ is Basis for subspace $U$  
$a \in U$ has unique combination $a = \sum c_iv_i$
### proof
Let's the other combination $a=\sum d_iv_i$  
now, $a-a = \sum c_iv_i - \sum d_iv_i \implies \mathbf{0} = \sum{(c_i-d_i)}v_i$   
but these vectors are basis So, only solution to equation that all of constant is 0  
$\therefore c_i = d_i$

So, basis for some subspace any member that present unique combination 