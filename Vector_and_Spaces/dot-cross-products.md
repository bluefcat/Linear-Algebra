# Dot cross products

## Dot products
signified by $a \cdot b$  

$\begin{bmatrix}a_1\\a_2\\\vdots\\a_n\end{bmatrix} \cdot \begin{bmatrix}b_1\\b_2\\\vdots\\b_n\end{bmatrix}=\sum a_ib_i$  

dot product result is real scalar

### Example  
$\begin{bmatrix}2\\5\end{bmatrix}\cdot \begin{bmatrix}7\\1\end{bmatrix}=7\times2+5\times1=19$  

$\begin{bmatrix}1\\2\\3\end{bmatrix}\cdot \begin{bmatrix}-2\\0\\5\end{bmatrix}=1\times(-2)+2\times0+3\times5=13$  

<br></br>  

## Length of vector  

Abstract to beyond $\mathbb{R}^3$

$||a||=\sqrt{\sum a_i^2}$

### Example  
$b = \begin{bmatrix}2\\5\end{bmatrix},\quad||b||=\sqrt{2^2+5^2}=\sqrt{29}$  

## Dot product and Length of vector

$a\cdot a = \begin{bmatrix}a_1\\a_2\\\vdots\\a_n\end{bmatrix}\cdot\begin{bmatrix}a_1\\a_2\\\vdots\\a_n\end{bmatrix}=\sum a_i^2=||a||^2$  

## Basic property dot product  
- **dot products has commutative property**  
  
  $v\cdot w = w\cdot v$  

  $v = \begin{bmatrix}v_1\\v_2\\\vdots\\v_n\end{bmatrix} w = \begin{bmatrix}w_1\\w_2\\\vdots\\w_n\end{bmatrix}$  

  $v \cdot w = \sum v_iw_i$  

  $w \cdot v = \sum w_iv_i$  

  $\therefore v \cdot w = w \cdot v$ (commutative property)
<br></br>

- **dot products has distributivity property**  
  
  $x = \begin{bmatrix}x_1\\x_2\\\vdots\\x_n\end{bmatrix}$  

  $(v+w)\cdot x=v\cdot x + w\cdot x$  

  $(v+w)\cdot x=\begin{bmatrix}v_1+w_1\\v_2+w_2\\\vdots\\v_n+w_n\end{bmatrix}\cdot \begin{bmatrix}x_1\\x_2\\\vdots\\x_n\end{bmatrix}=\sum (v_i+w_i)x_i$  

  $v\cdot x = \sum v_ix_i$  

  $w\cdot x = \sum w_ix_i$  
  
  $v\cdot x + w\cdot x = \sum v_ix_i + \sum w_ix_i = \sum(v_i+w_i)x_i$  

  $\therefore (v+w)\cdot x=v\cdot x + w\cdot x$ (distributivity property)  
<br></br>

- **dot product has Associativity property**  
  
  $\{(cv)\cdot w = c(v\cdot w)\;|\; c\;\text{is}\;scalar\}$  

  $cv = \begin{bmatrix}cv_1\\cv_2\\\vdots\\cv_n\end{bmatrix}\cdot w = \sum cv_iw_i$  

  $c(v \cdot w) = c\sum v_iw_i = \sum cv_iw_i$ 

  $\therefore (cv)\cdot w = c(v\cdot w)$ (associativity propery)