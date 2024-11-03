# 行列式的性质

* [基本性质](#基本性质)
* [逆序数](#逆序数)
* [余子式](#余子式)
* [重要行列式](#重要行列式)
  * [主对角线行列式](#主对角线行列式)
  * [副对角线行列式](#副对角线行列式)
  * [拉普拉斯展开式](#拉普拉斯展开式)
  * [范德蒙德行列式](#范德蒙德行列式)

* [经典例题](#经典例题)

## 基本性质

$$
行列互换，其值不变，即 |A| = |A ^ T| .
$$

$$
若行列式中某行（列）元素全为零，则行列式为零.
$$

$$
行列式中的两行（列）元素相等或对应成比例，则行列式为零.
$$

$$
行列式中某行（列）元素均是两个数之和，则可拆成两个行列式之和，即
\\\
\
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{i1} + b_{i1} & a_{i2} + b_{i2} & \cdots & a_{in} + b_{in} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{i1} & a_{i2} & \cdots & a_{in} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
+
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \vdots & \vdots \\
b_{i1} & b_{i2} & \cdots & b_{in} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix} .
$$

$$
倍乘性质：若行列式中某行（列）元素有公因子 k (k \neq 0) ，则 k 可提到行列式外面，即
\
\\
\
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \vdots & \vdots \\
ka_{i1} & ka_{i2} & \cdots & ka_{in} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
=
k\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{i1} & a_{i2} & \cdots & a_{in} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix} .
$$

$$
互换性质：行列式中两行（列）互换，行列式变号.
$$

$$
倍加性质：行列式中某行（列）的 k 倍加到另一行（列），行列式不变.
$$

## 逆序数

$$
在一个 n 级排列 {i_1}{i_2} \cdots {i_s} \cdots {i_t} \cdots {i_n} 中，若 i_s \gt i_t ，且 i_s 排在 i_t 前面，则称这两个数构成一个逆序.
$$

$$
一个排列中，逆序的总数称为该排列的逆序数，记作 \tau({i_1}{i_2} \cdots {i_n}) ，如 \tau(231546) = 3 , \tau(621534) = 8 .
$$

$$
排列的逆序数为奇数时，该排列称为奇排列；排列的逆序数为偶数时，该排列称为偶排列.
$$

## 余子式

$$
在 n 阶行列式中，去掉元素 a_{ij} 所在的第 i 行、第 j 列元素，由剩下的元素按原来的位置与顺序组成的 n - 1 阶行列式称为元素 a_{ij} 的余子式，记作 M_{ij} .
$$

$$
余子式 M_{ij} 乘 (-1) ^ {i + j} 后称为 a_{ij} 的代数余子式，记作 A_{ij} ，即 A_{ij} = (-1) ^ {i + j}{M_{ij}} .
$$

$$
行列式等于行列式的某行（列）元素分别乘其相应的代数余子式后再求和，即 D = a_{i1}A_{i1} + a_{i2}A_{i2} + \cdots + a_{in}A_{in} .
$$

## 重要行列式

### 主对角线行列式

$$
\begin{vmatrix}
a_{11} & 0 & \cdots & 0 \\
0 & a_{22} & \cdots & 0 \\
\vdots & \vdots & \vdots & \vdots \\
0 & 0 & \cdots & a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
0 & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \vdots & \vdots \\
0 & 0 & \cdots & a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} & 0 & \cdots & 0 \\
a_{21} & a_{22} & \cdots & 0 \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
= a_{11}a_{22} \cdots a_{nn} .
$$

### 副对角线行列式

$$
\begin{vmatrix}
0 & \cdots & 0 & a_{1n} \\
0 & \cdots & a_{2 , n - 1} & 0 \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & \cdots & 0 & 0
\end{vmatrix}
=
\begin{vmatrix}
0 & \cdots & 0 & a_{1n} \\
0 & \cdots & a_{2 , n - 1} & a_{2n} \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & \cdots & a_{n , n - 1} & a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} & \cdots & a_{1 , n - 1} & a_{1n} \\
a_{21} & \cdots & a_{2 , n - 1} & 0 \\
\vdots & \vdots & \vdots & \vdots \\
a_{n1} & \cdots & 0 & 0
\end{vmatrix}
= (-1) ^ {\frac{n(n-1)}{2}}{a_{1n}}{a_{2 , n - 1}} \cdots {a_{n1}} .
$$

### 拉普拉斯展开式

$$
设 A 为 m 阶行列式， B 为 n 阶行列式，则
\\
\begin{vmatrix}
A & O\\
O & B
\end{vmatrix}
=
\begin{vmatrix}
A & C\\
O & B
\end{vmatrix}
=
\begin{vmatrix}
A & O\\
C & B
\end{vmatrix}
= |A||B| .
\\
\begin{vmatrix}
O & A\\
B & O
\end{vmatrix}
=
\begin{vmatrix}
O & A\\
B & C
\end{vmatrix}
=
\begin{vmatrix}
C & A\\
B & O
\end{vmatrix}
= (-1) ^ {mn} |A||B| .
$$

### 范德蒙德行列式

$$
\begin{vmatrix}
1 & 1 & \cdots & 1 \\
x_{1} & x_{2} & \cdots & x_{n}\\
\cdots & \cdots & \cdots & \cdots\\
x_{1} ^ {n-1} & x_{2} ^ {n-1} & \cdots & x_{n} ^ {n-1}
\end{vmatrix}
= \prod_{1 \le i \le j \le n}(x_j - x_i) .
$$

## 经典例题

$$
如：求
\begin{vmatrix}
1 & 1 & 1 & 1 \\
1 & 2 & 0 & 0 \\
1 & 0 & 3 & 0 \\
1 & 0 & 0 & 4
\end{vmatrix} .
\\
\begin{vmatrix}
1 & 1 & 1 & 1 \\
1 & 2 & 0 & 0 \\
1 & 0 & 3 & 0 \\
1 & 0 & 0 & 4
\end{vmatrix}
=
1 \cdot (-1) ^ {(1 + 4)} \cdot
\begin{vmatrix}
1 & 2 & 0 \\
1 & 0 & 3 \\
1 & 0 & 0
\end{vmatrix}
+
4 \cdot (-1) ^ {(4 + 4)} \cdot
\begin{vmatrix}
1 & 1 & 1 \\
1 & 2 & 0 \\
1 & 0 & 3
\end{vmatrix}
\\
\
=
(-1) \cdot 3 \cdot (-1) ^ {(2 + 3)}
\begin{vmatrix}
1 & 2 \\
1 & 0
\end{vmatrix}
+
4 \cdot
\begin{vmatrix}
1 & 1 & 2 \\
0 & 1 & 0 \\
1 & 0 & 3
\end{vmatrix}
= 3 \cdot (-2) + 4 \cdot 1 \cdot (-1) ^ {(2 + 2)}
\begin{vmatrix}
1 & 2 \\
1 & 3
\end{vmatrix}
= -6 + 4 = -2 .
$$



