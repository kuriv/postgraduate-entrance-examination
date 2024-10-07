# 克拉默法则

* [定理内容](#定理内容)

## 定理内容

$$
非齐次线性方程组
\begin{cases}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = b_1 , \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n = b_2 , \\
\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \cdots\cdots \\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = b_n ，
\end{cases}
若系数行列式 D = 
\begin{vmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n} \\
a_{21} \ a_{22} \ \cdots \ a_{2n} \\
\cdots \ \cdots \ \cdots \ \cdots \\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix}
\neq 0 ，则方程组有唯一解，
\\
且解为 x_i = \frac{D_i}{D} ， i = 1 , 2 , \cdots , n ，其中 D_i 是由常数项 b1 , b2 , \cdots , b_n 替换 D 中第 i 列元素得到的行列式.
$$

$$
齐次线性方程组
\begin{cases}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = 0 , \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n = 0 , \\
\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \cdots\cdots \\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = 0 ，
\end{cases}
若 D \neq 0 ，则齐次线性方程组只有零解；若 D = 0 ，则齐次线性方程组有非零解.
$$

$$
非齐次线性方程有唯一解的充分必要条件是 D \neq 0 ，当 D = 0 时，要么无解，要么有无穷多个解.
\\
齐次线性方程只有零解的充分必要条件是 D \neq 0 ，有非零解的充分必要条件是 D = 0 .
$$



