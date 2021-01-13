# Linear subspace

subspace of $\mathbb{R}^n$  

## Definition 
$\mathbb{V} \gets \text{subset of}\;\mathbb{R}^n$  
$\mathbb{V}$ is linear subspace of $\mathbb{R}^n$. This mean that
- $\mathbb{V}$ contains zero vector
  
- $\mathbf{x}$ in $\mathbb{V}$ multiply any member on real, it($c\mathbf{x}$) in $\mathbb{V}$  
(this is "closure under Scalar multiplecation")

- take two vector $\mathbf{a}, \mathbf{b} \in \mathbf{V}$ so, $\mathbf{a} + \mathbf{b} \in \mathbf{V}$  
(closure under addition)

## Example
Is $V = \begin{bmatrix}0\\0\\0\end{bmatrix}$ subspace of $\mathbb{R}^3$ ?  
- $V$ contains zero vector
  
- closure under multiplecation  
  $c\begin{bmatrix}0\\0\\0\end{bmatrix} \in V$

- closure under addition

$\therefore V$ is subspace of $\mathbb{R}^3$
<br></br>
Is $S = \left\{\begin{bmatrix}x_1\\x_2\end{bmatrix}\in\mathbb{R}^2\;|\;x_1\ge0\right\}$ subspace of $\mathbb{R}^2$ ?
- $S$ contains zero vector
  
- closure under addition

- not closure under multiplecation  
$-1\begin{bmatrix}x_1\\x_2\end{bmatrix}$ has negative number on $x_1$

$\therefore S$ isn't subspace of $\mathbb{R}^2$
<br></br>
Is $U = \{\text{span}(v_1, v_2, \cdots v_n)\;|\;n\in\mathbb{N}\}$ valid subspace of $\mathbb{R}^n$  

- $U$ contains zero vector  
$\sum c_iv_i = 0 \impliedby c_i = 0$

- closure under multiplecation  
$a\sum c_iv_i = \sum ac_iv_i$  
$ac_i$ is other constance number. Cleary this is one of linear combination

- closure under addition  
  $\sum c_iv_i + \sum d_iv_i = \sum (c_i + d_i)v_i$  
  $(c_i + d_i)$ is other constance number. So this is another of linear combination

$\therefore U$ is subspace of $\mathbb{R}^n$