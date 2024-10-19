# 非齐次线性方程组

* [有解条件](#有解条件)
* [求解步骤](#求解步骤)
* [经典例题](#经典例题)

## 有解条件

$$
若 r(A) \neq r([A , b]) (b 不能由 \alpha_1 , \alpha_2 , \cdots , \alpha_n 线性表示) ，则方程组无解.
\\
若 r(A) = r([A , b]) = n (\alpha_1 , \alpha_2 , \cdots , \alpha_n 线性无关， \alpha_1 , \alpha_2 , \cdots , \alpha_n , b 线性相关) ，则方程组有唯一解.
\\
若 r(A) = r([A , b]) = r \lt n ，则方程组有无穷多解.
$$

## 求解步骤

$$
先写出 Ax = b 的导出方程组 Ax = 0 ，并求 Ax = 0 的通解 k_1\xi_1 + k_2\xi_2 + \cdots + k_{n - r}\xi_{n - r} ，
\\
然后求出 Ax = b 的一个特解，
\\
最后得到 Ax = b 的通解为 k_1\xi_1 + k_2\xi_2 + \cdots + k_{n - r}\xi_{n - r} + \eta ，其中 k_1 ， k_2 ， \cdots ， k_{n - r} 为任意常数.
$$

## 经典例题

$$
设 A =
\begin{pmatrix}
\lambda & 1 & 1 \\
0 & \lambda - 1 & 0 \\
1 & 1 & \lambda
\end{pmatrix}
， b =
\begin{pmatrix}
a \\
1 \\
1
\end{pmatrix}
，已知线性方程组 Ax = b 存在两个不同的解，求 \lambda 和 a 的值，并求方程组 Ax = b 的通解.
\\
\because |A| =
\begin{vmatrix}
\lambda & 1 & 1 \\
0 & \lambda - 1 & 0 \\
1 & 1 & \lambda
\end{vmatrix}
= {(\lambda - 1) ^ 2}(\lambda + 1) = 0 ，
\\
\therefore \lambda = 1 或 -1 ，
\\
当 \lambda = 1 ，
\begin{pmatrix}
A & \vdots & b
\end{pmatrix}
=
\begin{pmatrix}
1 & 1 & 1 & \vdots & a \\
0 & 0 & 0 & \vdots & 1 \\
1 & 1 & 1 & \vdots & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 1 & 1 & \vdots & 1 \\
0 & 0 & 0 & \vdots & 1 \\
0 & 0 & 0 & \vdots & a - 1
\end{pmatrix} ，
\\
\therefore \lambda = 1 舍去，
\\
当 \lambda = -1 ，
\begin{pmatrix}
A & \vdots & b
\end{pmatrix}
=
\begin{pmatrix}
-1 & 1 & 1 & \vdots & a \\
0 & -2 & 0 & \vdots & 1 \\
1 & 1 & -1 & \vdots & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 1 & -1 & \vdots & 1 \\
0 & -2 & 0 & \vdots & 1 \\
0 & 0 & 0 & \vdots & a + 2
\end{pmatrix} ，
\\
\therefore a = -2 ，
\\
\therefore 综上， \lambda = -1 ， a = -2 ，
\\\
\
\therefore \xi_1 = [1 , 0 , 1] ， \xi_2 = [\frac{3}{2} , -\frac{1}{2} , 1] ，
\\
\therefore 通解为 k{[1 , 0 , 1]} ^ {T} + [\frac{3}{2} , -\frac{1}{2} , 1] ^ {T} ，其中 k 为任意常数.
$$



