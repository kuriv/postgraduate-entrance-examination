# 极大线性无关组

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
在向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_s 中，若存在部分组 \alpha_{i_1} ， \alpha_{i_2} ， \cdots ， \alpha_{i_r} 满足：
\\
\alpha_{i_1} ， \alpha_{i_2} ， \cdots ， \alpha_{i_r} 线性无关，且向量组中任一向量 \alpha_i (i = 1 , 2 , \cdots , s) 均可由 \alpha_{i_1} ， \alpha_{i_2} ， \cdots ， \alpha_{i_r} 线性表示，
\
\\
则称向量组 \alpha_{i_1} ， \alpha_{i_2} ， \cdots ， \alpha_{i_r} 是原向量组的极大线性无关组.
$$

$$
求极大线性无关组的步骤：将所有列向量组成矩阵 A ，作初等行变换，化为行阶梯形矩阵，并确定 r(A) ，
\\
按列找出一个秩为 r(A) 的子矩阵，即为一个极大线性无关组.
$$

## 经典例题

$$
设向量组 \alpha_1 = [1 , -1 , 2 , 4] ^ {T} ， \alpha_2 = [0 , 3 , 1 , 2] ^ {T} ， \alpha_3 = [3 , 0 , 7 , 14] ^ {T} ， \alpha_4 = [1 , -2 , 2 , 0] ^ {T} ， \alpha_5 = [2 , 1 , 5 , 10] ^ {T} ， 求该向量组的极大线性无关组.
\
\\
\
令 A = [\alpha_1 ， \alpha_2 ， \alpha_3 ， \alpha_4 ， \alpha_5] =
\begin{pmatrix}
1 & 0 & 3 & 1 & 2 \\
-1 & 3 & 0 & -2 & 1 \\
2 & 1 & 7 & 2 & 5 \\
4 & 2 & 14 & 0 & 10
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 3 & 0 & 2 \\
0 & 1 & 1 & 0 & 1 \\
0 & 0 & 0 & 1 & 0 \\
0 & 0 & 0 & 0 & 0
\end{pmatrix} ,
\\
\therefore r(A) = 3 ，
\\
\therefore 该向量的极大线性无关组为 \alpha_1 ， \alpha_2 ， \alpha_4 或 \alpha_1 ， \alpha_3 ， \alpha_4 或 \alpha_1 ， \alpha_4 ， \alpha_5 或 \alpha_2 ， \alpha_3 ， \alpha_4 或 \alpha_2 ， \alpha_4 ， \alpha_5 或 \alpha_3 ， \alpha_4 ， \alpha_5 .
$$

$$
设 A =
\begin{pmatrix}
1 & -2 & -1 & 2 \\
2 & -3 & -2 & 3 \\
2 & -2 & -2 & 2 \\
1 & -1 & -1 & 1
\end{pmatrix}
= BC ， B =
\begin{pmatrix}
-1 & -2 \\
-2 & -3 \\
-2 & -2 \\
-1 & -1
\end{pmatrix}
，求 CB.
\\
令 A = [\alpha_1 ， \alpha_2 ， \alpha_3 ， \alpha_4 ， \alpha_5] =
\begin{pmatrix}
1 & -2 & -1 & 2 \\
2 & -3 & -2 & 3 \\
2 & -2 & -2 & 2 \\
1 & -1 & -1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & -1 & 0 \\
0 & 1 & 0 & -1 \\
0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0
\end{pmatrix} ，
\\
\therefore r(A) = 2 ，
\\
\therefore A 的极大线性无关组为 \alpha_3 ， \alpha_2 ， 且 \alpha_3 = -\alpha_1 ， \alpha_2 = -\alpha_4 ，
\\
\therefore A = [\alpha_1 ， \alpha_2 ， \alpha_3 ， \alpha_4 ， \alpha_5] = [\alpha_3 , \alpha_2]
\begin{pmatrix}
-1 & 0 & 1 & 0 \\
0 & 1 & 0 & -1 
\end{pmatrix}
=
\begin{pmatrix}
-1 & -2 \\
-2 & -3 \\
-2 & -2 \\
-1 & -1
\end{pmatrix}
\begin{pmatrix}
-1 & 0 & 1 & 0 \\
0 & 1 & 0 & -1 
\end{pmatrix}
= BC ，
\\
\therefore CB =
\begin{pmatrix}
-1 & 0 & 1 & 0 \\
0 & 1 & 0 & -1 
\end{pmatrix}
\begin{pmatrix}
-1 & -2 \\
-2 & -3 \\
-2 & -2 \\
-1 & -1
\end{pmatrix}
=
\begin{pmatrix}
-1 & 0 \\
-1 & -2
\end{pmatrix} .
$$



