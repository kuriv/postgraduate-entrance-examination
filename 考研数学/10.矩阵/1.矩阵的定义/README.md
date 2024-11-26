# 矩阵的定义

* [定理内容](#定理内容)
* [基本运算](#基本运算)
* [线性运算](#线性运算)
* [转置矩阵](#转置矩阵)
* [重要矩阵](#重要矩阵)
* [经典例题](#经典例题)

## 定理内容

$$
由 m \times n 个数 a_{ij} (i = 1 , 2 , \cdots , m ; j = 1 , 2 , \cdots , n) 排成的 m 行 n 列的矩形表格
\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{pmatrix}
称为一个 m \times n 矩阵，
\\
当 m = n 时，称 A 为 n 阶方阵.
$$

## 基本运算

$$
相等： A = (a_{ij})_{m \times n} = B = (b_{ij})_{s \times k} \Leftarrow\Rightarrow m = s , n = k ，且 a_{ij} = b_{ij} (i = 1 , 2 , \cdots , m ; j = 1 , 2 , \cdots , n) ，即 A ， B 是同型矩阵，且对应元素相等.
$$

$$
加法：两个矩阵是同型矩阵时，可以对应元素相加，即 C = A + B = (a_{ij})_{m \times n} + (b_{ij})_{m \times n} = (c_{ij})_{m \times n} .
$$

$$
数乘矩阵：设 k 是一个数， A 是一个 m \times n 矩阵，数 k 和 A 的乘积称为数乘矩阵，即
\\
kA = Ak = k
\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{pmatrix}
=
\begin{pmatrix}
ka_{11} & ka_{12} & \cdots & ka_{1n} \\
ka_{21} & ka_{22} & \cdots & ka_{2n} \\
\vdots & \vdots & \vdots & \vdots \\
ka_{m1} & ka_{m2} & \cdots & ka_{mn}
\end{pmatrix}
= (ka_{ij})_{m \times n} .
$$

$$
乘法：设 A 是一个 m \times s 矩阵， B 是一个 s \times n 矩阵（矩阵 A 的列数必须与矩阵 B 的行数相等），则 A ， B 可以相乘，乘积 AB 是 m \times n 矩阵.
$$

## 线性运算

$$
交换律： A + B = B + A .
$$

$$
结合律： (A + B) + C = A + (B + C) .
\\
(A_{m \times s}B_{s \times r})C_{r \times n} = A_{m \times s}(B_{s \times r}C_{r \times n}) .
$$

$$
分配律： k(A + B) = kA + kB ， (k + l)A = kA + lA .
\\
A_{m \times s}(B_{s \times n} + C_{s \times n}) = A_{m \times s}B_{s \times n} + A_{m \times s}C_{s \times n} ， (A_{m \times s} + B_{m \times s})C_{s \times n} = A_{m \times s}C_{s \times n} + B_{m \times s}C_{s \times n} .
$$

$$
数和矩阵相乘的结合律： k(lA) = (kl)A = l(kA) .
\\
(kA_{m \times s})B_{s \times n} = A_{m \times s}(kB_{s \times n}) = k(A_{m \times s}B_{s \times n}) .
$$

## 转置矩阵

$$
将 m \times n 矩阵 A = (a_{ij})_{m \times n} 的行与列互换得到的 n \times m 矩阵，称为矩阵 A 的转置矩阵，记为 A ^ {T} ，即
\\
A ^ {T} =
\begin{pmatrix}
a_{11} & a_{21} & \cdots & a_{m1} \\
a_{12} & a_{22} & \cdots & a_{m2} \\
\vdots & \vdots & \vdots & \vdots \\
a_{1n} & a_{2n} & \cdots & a_{mn}
\end{pmatrix} .
$$

$$
转置矩阵满足以下运算规律：
\\
(A ^ {T}) ^ {T} = A .
\\
(kA) ^ {T} = k{A ^ {T}} .
\\
(A + B) ^ {T} = A ^ {T} + B ^ {T} .
\\
(AB) ^ {T} = {B ^ {T}}{A ^ {T}} .
$$

## 重要矩阵

$$
零矩阵：每个元素均为零的矩阵，记为 O .
$$

$$
单位矩阵：主对角线元素均为 1 ，其余元素全为零的 n 阶方阵，称为 n 阶单位矩阵，记为 E .
$$

$$
数量矩阵：数 k 和单位矩阵的乘积的乘积称为数量矩阵.
$$

$$
对角矩阵：非主对角线运算均为零的矩阵称为对角矩阵.
$$

$$
上（下）三角矩阵：当 i \gt (\lt) j 时， a_{ij} = 0 的矩阵称为上（下）三角矩阵.
$$

$$
对称矩阵：满足条件 A ^ {T} = A 的矩阵 A 称为对称矩阵， A ^ {T} = A \Leftarrow\Rightarrow a_{ij} = a_{ji} .
$$

$$
反对称矩阵：满足条件 A ^ {T} = -A 的矩阵 A 称为反对称矩阵.
$$

$$
行矩阵：只有一行元素的矩阵，也称行向量.
$$

$$
列矩阵：只有一列元素的矩阵，也称列向量.
$$

## 经典例题

$$
如：设 \alpha = [a_1 , a_2 , a_3] ^ {T} ， \beta = [b_1 , b_2 , b_3] ^ {T} ， A = \alpha{\beta ^ {T}} ，求 A ^ {n} .
\\
\because \alpha{\beta ^ {T}} =
\begin{pmatrix}
a_1 \\
a_2 \\
a_3
\end{pmatrix}
[b_1 , b_2 , b_3] = 
\begin{pmatrix}
a_1b_1 & a_1b_2 & a_1b_3 \\
a_2b_1 & a_2b_2 & a_2b_3 \\
a_3b_1 & a_3b_2 & a_3b_3
\end{pmatrix} ， {\beta ^ {T}}\alpha = [b_1 , b_2 , b_3]
\begin{pmatrix}
a_1 \\
a_2 \\
a_3
\end{pmatrix}
= a_1b_1 + a_2b_2 + a_3b_3 ，
\\
\therefore A ^ n = (\alpha{\beta ^ {T}})(\alpha{\beta ^ {T}}) \cdots (\alpha{\beta ^ {T}}) = \alpha(\beta ^ {T}\alpha)(\beta ^ {T}\alpha) \cdots (\beta ^ {T}\alpha)\beta ^ {T} = {(\beta ^ {T}\alpha) ^ {n - 1}}\alpha{\beta ^ {T}}
\\
= {(a_1b_1 + a_2b_2 + a_3b_3) ^ {n - 1}}\alpha{\beta ^ {T}} = {(\sum_{i = 1} ^ {3}{a_ib_i}) ^ {n - 1}}A .
$$

$$
如：设 A =
\begin{pmatrix}
1 & -1 & -1 & -1 \\
-1 & 1 & -1 & -1 \\
-1 & -1 & 1 & -1 \\
-1 & -1 & -1 & 1
\end{pmatrix}
，求 A ^ {9} .
\\
\because A ^ {2} = AA =
\begin{pmatrix}
1 & -1 & -1 & -1 \\
-1 & 1 & -1 & -1 \\
-1 & -1 & 1 & -1 \\
-1 & -1 & -1 & 1
\end{pmatrix}
\begin{pmatrix}
1 & -1 & -1 & -1 \\
-1 & 1 & -1 & -1 \\
-1 & -1 & 1 & -1 \\
-1 & -1 & -1 & 1
\end{pmatrix}
=
\begin{pmatrix}
4 & 0 & 0 & 0 \\
0 & 4 & 0 & 0 \\
0 & 0 & 4 & 0 \\
0 & 0 & 0 & 4
\end{pmatrix}
= 4E ，
\
\\
\therefore A ^ {9} = {(A ^ {2}) ^ {4}}A = {4 ^ {4}}A = 256A .
$$

$$
如：已知 A =
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{pmatrix}
，求 A ^ {n} .
\\
\because A =
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
+
\begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix} ，
\\
令 B =
\begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix}
，则 A = E + B ，
\\
\therefore A ^ {n} = (E + B) ^ {n} = E ^ {n} + n{E ^ {n - 1}}B + \frac{n(n - 1)}{2!}{E ^ {n - 2}}{B ^ {2}} + \frac{n(n - 1)(n - 2)}{3!}{E ^ {n - 3}}{B ^ {3}} + \cdots + B ^ {n} ，
\\
\because B ^ {2} =
\begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix}
\begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix}
=
\begin{pmatrix}
0 & 0 & 1 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix}
， B ^ {3} =
\begin{pmatrix}
0 & 0 & 1 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix}
\begin{pmatrix}
0 & 1 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix}
=
\begin{pmatrix}
0 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix}
= O ，
\
\\
\therefore A ^ {n} = (E + B) ^ {n} = E ^ {n} + n{E ^ {n - 1}}B + \frac{n(n - 1)}{2!}{E ^ {n - 2}}{B ^ {2}} = E + nB + \frac{n(n - 1)}{2!}B ^ {2}
\\
=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
+
\begin{pmatrix}
0 & n & 0 \\
0 & 0 & n \\
0 & 0 & 0
\end{pmatrix}
+
\begin{pmatrix}
0 & 0 & \frac{n(n - 1)}{2} \\
0 & 0 & 0 \\
0 & 0 & 0
\end{pmatrix}
=
\begin{pmatrix}
1 & n & \frac{n(n - 1)}{2} \\
0 & 1 & n \\
0 & 0 & 1
\end{pmatrix} .
$$



