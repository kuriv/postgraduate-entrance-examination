# 特征值与特征向量

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 A 是 n 阶矩阵， \lambda 是一个数，若存在 n 维非零列向量 \xi ，使得 A\xi = \lambda\xi ，
\\
则称 \lambda 是 A 的特征值， \xi 是 A 的对应于特征值 \lambda 的特征向量.
$$

$$
求解具体型矩阵的特征值与特征向量，一般先用特征方程 |\lambda{E} - A| = 0 求出 \lambda ，再解齐次线性方程组 (\lambda{E} - A)x = 0 ，求出特征向量.
$$

## 经典例题

$$
求矩阵 A =
\begin{pmatrix}
2 & 2 & -2 \\
2 & 5 & -4 \\
-2 & -4 & 5
\end{pmatrix}
的特征值与特征向量.
\\
令 |\lambda{E} - A| =
\begin{vmatrix}
\lambda - 2 & -2 & 2 \\
-2 & \lambda - 5 & 4 \\
2 & 4 & \lambda - 5
\end{vmatrix}
=
\begin{vmatrix}
\lambda - 2 & -2 & 0 \\
-2 & \lambda - 5 & \lambda - 1 \\
2 & 4 & \lambda - 1
\end{vmatrix}
=
\begin{vmatrix}
\lambda - 2 & -2 & 0 \\
-4 & \lambda - 9 & 0 \\
2 & 4 & \lambda - 1
\end{vmatrix}
= (\lambda - 1)(\lambda ^ 2 - 11\lambda + 10) = {(\lambda - 1) ^ 2}(\lambda - 10) = 0 ，
\\
\therefore A 的特征值为 \lambda_1 = \lambda_2 = 1 ， \lambda_3 = 10 ，
\\
当 \lambda_1 = \lambda_2 = 1 时， (E - A)x =
\begin{pmatrix}
-1 & -2 & 2 \\
-2 & -4 & 4 \\
2 & 4 & -4
\end{pmatrix}
\begin{pmatrix}
x_1 \\
x_2 \\
x_3
\end{pmatrix}
= 0 ，
\\
\therefore \xi_1 = [-2 , 1 , 0] ^ T ， \xi_2 = [2 , 0 , 1] ^ T ， k_1\xi_1 + k_2\xi_2 为 \lambda_1 = \lambda_2 = 1 的全部特征向量，且 k_1 ， k_2 \neq 0 ，
\\
当 \lambda_3 = 10 时， (10E - A)x =
\begin{pmatrix}
8 & -2 & 2 \\
-2 & 5 & 4 \\
2 & 4 & 5
\end{pmatrix}
\begin{pmatrix}
x_1 \\
x_2 \\
x_3
\end{pmatrix}
= 0 ，
\\
\therefore \xi_3 = [-\frac{1}{2} , -1 , 1] ^ T ， k_3\xi_3 为\lambda_3 = 10 的全部特征向量，且 k_3 \neq 0 .
$$



