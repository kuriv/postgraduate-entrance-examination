# 行列式

* [定理内容](#定理内容)
* [特殊的高阶行列式](#特殊的高阶行列式)
  * [对角行列式](#对角行列式)
  * [范德蒙行列式](#范德蒙行列式)
  * [分块行列式](#分块行列式)

* [行列式的计算性质](#行列式的计算性质)
* [克拉默法则](#克拉默法则)

## 定理内容

$$
定义：设 i , j 是一对不等的正整数，若 i \gt j ，则称 (i , j) 为一对逆序数.
$$

$$
定义：设 i_1 , i_2 \cdots , i_n 是 1, 2， \cdots n 的一个排列，该排列所含的逆序总数称为该排列的逆序数，记为 \tau(i_1 , i_2 \cdots , i_n) ，
\\
逆序数为奇数的排列称为奇排列，逆序数为偶数的排列称为偶排列，如 \tau(421635) = 3 + 1 + 0 + 2 + 0 = 6 .
$$

$$
定义：由 n ^ 2 个数组成的记号 D = \begin{vmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix} ，称为 n 阶行列式，规定 D = \sum_{{j_1}{j_2}{\cdots}{j_n}}(-1) ^ {\tau({j_1}{j_2}{\cdots}{j_n})}{a_{1j_1}}{a_{2j_2}}\cdots{a_{nj_n}} .
$$

$$
定义：把行列式 D = \begin{vmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix} 中元素 a_{ij} 所在的第 i 行元素和第 j 列元素去掉，剩下的 n-1 行和 n-1 列按照原来的排列次序构成的 n-1 阶行列式，
\\
称为元素 a_{ij}的余子式，记为 M_{ij} ，称 A_{ij} = (-1) ^ {i + j}M_{ij} 为元素 a_{ij} 的代数余子式.
$$

## 特殊的高阶行列式

### 对角行列式

$$
\begin{vmatrix}
a_{11} \ \ 0 \ \ \cdots \ \ 0 \ \ \\
\ \ 0 \ \ a_{22} \cdots \ \ 0 \ \ \\
\cdots \ \cdots \ \cdots \ \cdots\\
\ \ 0 \ \ \ 0 \ \cdots \ a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} \ a_{12} \cdots a_{1n} \\
\ \ 0 \ \ a_{22} \cdots a_{2n} \\
\cdots \ \cdots \ \cdots \ \cdots\\
\ \ 0 \ \ \ 0 \ \cdots \ a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} \ \ 0 \ \ \cdots \ \ 0 \ \ \\
a_{21} \ a_{22} \cdots \ \ 0 \ \ \\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \cdots \ a_{nn}
\end{vmatrix}
= a_{11}a_{22} \cdots a_{nn} .
$$

$$
\begin{vmatrix}
\ \ 0 \ \ \ \ 0 \ \ \ \ 0 \ \ \ \ l_1 \\
\ \ 0 \ \ \ \ 0 \ \ \ \ l_2 \ \ \ 0 \ \\
\ \ 0 \ \ \cdots \ \ 0 \ \ \ \ 0 \ \\
\ \ l_n \ \ \ 0 \ \ \ \ 0 \ \ \ \ 0 \
\end{vmatrix}
= (-1) ^ {\frac{n(n-1)}{2}}{l_1}{l_2} \cdots {l_n} .
$$

### 范德蒙行列式

$$
\begin{vmatrix}
1 \ \ \ \ \ 1 \ \ \ \ \ \cdots \ \ \ \ \ 1 \\
a_{1} \ \ \ \ a_{2} \ \ \ \ \cdots \ \ \ \ a_{n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{1} ^ {n-1} \ a_{2} ^ {n-1} \ \cdots \ a_{n} ^ {n-1}
\end{vmatrix}
= \Pi_{1 \le j \le i \le n}(a_i - a_j) .
$$

### 分块行列式

$$
\begin{vmatrix}
A \ C\\
O \ B
\end{vmatrix}
=
\begin{vmatrix}
A \ O\\
C \ B
\end{vmatrix}
=
\begin{vmatrix}
A
\end{vmatrix}
\begin{vmatrix}
B
\end{vmatrix} .
$$

## 行列式的计算性质

$$
行列式与其转置行列式相等，即 D = D ^ T .
$$

$$
对调两行（或列）行列式改变符号.
$$

$$
行列式某行（或列）有公因子可以提取到行列式的外面.
$$

$$
若行列式某行（或列）元素全为零，则该行列式值为零.
$$

$$
若行列式某两行（或列）元素相同，则该行列式值为零.
$$

$$
若行列式某两行（或列）元素对应成比例，则该行列式值为零.
$$

$$
行列式某行（或列）的每个元素均为两数之和时，行列式可分解为两个行列式之和.
$$

$$
行列式某行（或列）的倍数加到另一行（或列），行列式不变.
$$

$$
行列式等于行列式某行（或列）元素与其对应的代数余子式之积的和，即 D = a_{i1}A_{i1} + a_{i2}A_{i2} + \cdots + a_{in}A_{in} .
$$

$$
行列式的某行（或列）元素与另一行（或列）对应元素的代数余子式之积的和为零，即 a_{i1}A_{j1} + a_{i2}A_{j2} + \cdots + a_{in}A_{jn} = 0 .
$$

## 克拉默法则

$$
对线性方程组 \begin{cases}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = 0 , \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n = 0 , \\
\cdots \\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = 0
\end{cases}
及
\begin{cases}
a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n = b_1 , \\
a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n = b_2 , \\
\cdots \\
a_{n1}x_1 + a_{n2}x_2 + \cdots + a_{nn}x_n = b_n
\end{cases} ，
\\
令 D = \begin{vmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix} ，
D_1 = \begin{vmatrix}
b_1 \ \ a_{12} \ \cdots \ a_{1n}\\
b_2 \ \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
b_n \ \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix} ，
D2 = \begin{vmatrix}
a_{11} \ \ b_1 \ \cdots \ a_{1n}\\
a_{21} \ \ b_2 \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ \ b_n \ \cdots \ a_{nn}
\end{vmatrix} ，
\\
齐次线性方程只有零解的充分必要条件是 D \neq 0 ， 有非零解的充分必要条件是 D = 0 ，
\\
非齐次线性方程有唯一解的充分必要条件是 D \neq 0 ，当 D = 0 时，要么无解，要么有无穷多个解.
$$



