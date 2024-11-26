# 矩阵的秩

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 A 是 m \times n 矩阵，若存在 k 阶子式不为零，而任意 k + 1 阶子式（如果有的话）全为零，则 r(A) = k .
$$

$$
若 A 是 n \times n 矩阵，则 r(A_{n \times n}) = n \Leftarrow\Rightarrow |A| \neq 0 \Leftarrow\Rightarrow A 可逆.
$$

$$
将 A 用初等行变换化为行阶梯形矩阵，其非零行数就是 A 的秩.
$$

$$
0 \le r(A) \le \min\{m , n\} .
\\
r(kA) = r(A) (k \neq 0) .
\\
r(AB) \le \min\{r(A) , r(B)\} .
\\
r(A + B) \le r(A) + r(B) .
\\
r(A ^ {*}) =
\begin{cases}
n ， r(A) = n ， \\
1 ， r(A) = n - 1 ， 其中 A 为 n (n \ge 2) 阶方阵， \\
0 ， r(A) \lt n - 1 .
\end{cases}
\\
r(A) = r(PA) = r(AQ) = r(PAQ) .
\\
A_{m \times n}B_{n \times s} = O ，则 r(A) + r(B) \le n .
\\
r(A) = r(A ^ {T}) = r({A ^ {T}}A) = r(A{A ^ {T}}) .
$$

## 经典例题

$$
如：若矩阵
\begin{pmatrix}
1 & 2 & -1 & 1 \\
2 & 0 & t & 0 \\
0 & -4 & 5 & -2
\end{pmatrix}
的秩为 2 ，求 t .
\\
\begin{pmatrix}
1 & 2 & -1 & 1 \\
2 & 0 & t & 0 \\
0 & -4 & 5 & -2
\end{pmatrix}
=
\begin{pmatrix}
1 & 2 & -1 & 1 \\
0 & -4 & t + 2 & -2 \\
0 & -4 & 5 & -2
\end{pmatrix}
=
\begin{pmatrix}
1 & 2 & -1 & 1 \\
0 & -4 & t + 2 & -2 \\
0 & 0 & 3 - t & 0
\end{pmatrix} ，
\
\\
\therefore 3 - t = 0 ， t = 3 .
$$



