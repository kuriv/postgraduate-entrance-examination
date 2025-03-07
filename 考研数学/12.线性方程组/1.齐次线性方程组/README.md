# 齐次线性方程组

* [有解条件](#有解条件)
* [基础解系](#基础解系)
* [求解步骤](#求解步骤)
* [经典例题](#经典例题)

## 有解条件

$$
当 r(A) = r = n (\alpha_1 , \alpha_2 , \cdots , \alpha_n 线性无关) 时，方程组只有零解（唯一解）.
\\
当 r(A) = r \lt n (\alpha_1 , \alpha_2 , \cdots , \alpha_n 线性相关) 时，方程组有非零解（无穷多解），且有 n - r 个线性无关解.
$$

## 基础解系

$$
设 \xi_1 ， \xi_2 ， \cdots ， \xi_n 是方程组 Ax = 0 的解，且 \xi_1 ， \xi_2 ， \cdots ， \xi_n 线性无关，
\\
则方程组 Ax = 0 的任一解均可由 \xi_1 ， \xi_2 ， \cdots ， \xi_n 线性表示，称 \xi_1 ， \xi_2 ， \cdots ， \xi_n 为 Ax = 0 的基础解系.
$$

## 求解步骤

$$
先将系数矩阵 A 作初等行变换化成行阶梯形矩阵 B （或行最简阶梯形矩阵 B），并记 r(A) = r ,
\\
然后按列找出一个秩为 r 的子矩阵，剩余列位置的未知数设为自由变量，
\\
最后按基础解系定义求出 \xi_1 ， \xi_2 ， \cdots ， \xi_{n - r} ，并写出通解.
$$

## 经典例题

$$
如：求齐次线性方程组
\begin{cases}
x_1 + x_2 - 3{x_4} - x_5 = 0 ， \\
x_1 - x_2 + 2{x_3} - x_4 = 0 ， \\
4{x_1} - 2{x_2} + 6{x_3} + 3{x_4} - 4{x_5} = 0 ， \\
2{x_1} + 4{x_2} - 2{x_3} + 4{x_4} - 7{x_5} = 0
\end{cases}
的通解.
\\
令 A =
\begin{pmatrix}
1 & 1 & 0 & -3 & -1 \\
1 & -1 & 2 & -1 & 0 \\
4 & -2 & 6 & 3 & -4 \\
2 & 4 & -2 & 4 & -7
\end{pmatrix}
=
\begin{pmatrix}
1 & 1 & 0 & -3 & -1 \\
0 & -2 & 2 & 2 & 1 \\
0 & 0 & 0 & 3 & -1 \\
0 & 0 & 0 & 0 & 0
\end{pmatrix} ，
\\
\therefore r(A) = 3 ，
\\
\therefore \xi_1 = [-1 , 1 , 1 , 0 , 0] ， \xi_2 = [\frac{7}{6} , \frac{5}{6} , 0 , \frac{1}{3} , 1] ，
\\\
\
\therefore 通解为 k_1{[-1 , 1 , 1 , 0 , 0] ^ {T}} + k_2{[\frac{7}{6} , \frac{5}{6} , 0 , \frac{1}{3} , 1] ^ {T}} ，其中 k_1 ， k_2 为任意常数.
$$



