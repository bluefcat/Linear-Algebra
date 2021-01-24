# Proof relationship between cross product and sin of angle

$\begin{bmatrix}a_1\\a_2\\a_3\end{bmatrix}\times \begin{bmatrix}b_1\\b_2\\b_3\end{bmatrix}=\begin{bmatrix}a_2b_3-a_3b_2\\a_3b_1-a_1b_3\\a_1b_2-a_2b_1\end{bmatrix}$  

this idea is start $||a\times b||^2$  
(we know that $||a||\,||b||\cos{\theta} = a\cdot b=a_1b_1+a_2b_2+a_3b_3$)  
$$\begin{aligned}
    ||a\times b||^2&= (a_2b_3-a_3b_2)^2+(a_3b_1-a_1b_3)^2+(a_1b_2-a_2b_1)^2\\
    &= a_1^2(b_2^2+b_3^2)+a_2^2(b_1^2+b_3^2)+a_3^2(b_1^2+b_2^2)-2(a_2a_3b_2b_3+a_1a_3b_1b_3+a_1a_2b_1b_2)\\
    ||a\times b||^2 + ||a||^2||b||^2\cos^2{\theta}&=(a_1^2+a_2^2+a_3^2)(b_1^2+b_2^2+b_3^2)\\
    &= ||a||^2||b||^2\\
    ||a\times b||^2 &= ||a||^2||b||^2(1-\cos^2\theta)
\end{aligned}$$

$\therefore ||a\times b|| = ||a||\,||b||\sin\theta$
