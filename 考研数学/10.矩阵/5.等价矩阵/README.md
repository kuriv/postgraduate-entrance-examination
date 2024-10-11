# 等价矩阵

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 A ， B 均是 m \times n 矩阵，若存在可逆矩阵 P_{m \times m} ， Q_{n \times n} ，使得 PAQ = B ，则称 A ， B 是等价矩阵.
$$

## 经典例题

$$
设矩阵 A =
\begin{pmatrix}
1 & 0 & 1 \\
-1 & -1 & 1 \\
0 & 2 & a
\end{pmatrix}
， B =
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 0 & 0
\end{pmatrix}
，当矩阵 A 和 B 等价时，求 a ，并求一个可逆矩阵 P ，使得 PA = B .
\\
\because E_{12}(1)A =
\begin{pmatrix}
1 & 0 & 0 \\
1 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 & 1 \\
-1 & -1 & 1 \\
0 & 2 & a
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 2 & a
\end{pmatrix} = C ，
\\
\because E_{23}(2)C =
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 2 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 2 & a
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 0 & a + 4
\end{pmatrix} = D ，
\\
\therefore D =
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 0 & a + 4
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 1 \\
0 & -1 & 2 \\
0 & 0 & 0
\end{pmatrix}
= B ，
\\
\therefore a + 4 = 0 ， a = -4 ，
\\
\because E_{23}(2)E_{12}(1)A = B ， PA = B ，
\\
\therefore P = E_{23}(2)E_{12}(1) =
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 2 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 & 0 \\
1 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 0 \\
1 & 1 & 0 \\
2 & 2 & 1
\end{pmatrix} .
$$



