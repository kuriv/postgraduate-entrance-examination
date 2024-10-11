# 初等变换与初等矩阵

* [初等变换](#初等变换)
* [初等矩阵](#初等矩阵)
* [行阶梯形矩阵](#行阶梯形矩阵)
* [行最简阶梯形矩阵](#行最简阶梯形矩阵)
* [初等变换求逆矩阵](#初等变换求逆矩阵)
* [分块矩阵的逆](#分块矩阵的逆)
* [经典例题](#经典例题)

## 初等变换

$$
一个非零常数乘矩阵的某一行（列）.
\\
互换矩阵中某两行（列）的位置.
\\
将矩阵的某一行（列）的 k 倍加到另一行（列）.
$$

## 初等矩阵

$$
由单位矩阵经过一次初等变换得到的矩阵称为初等矩阵.
\\
对 n 阶矩阵 A 进行初等行变换，相当于在矩阵 A 的左边乘相应的初等矩阵.
\\
对 n 阶矩阵 A 进行初等列变换，相当于在矩阵 A 的右边乘相应的初等矩阵.
$$

## 行阶梯形矩阵

$$
若有零行（即元素全为零的行），则零行全都位于非零行的下方.
\\
各非零行左起第一个非零元素的列指标由上至下是严格增大的.
$$

## 行最简阶梯形矩阵

$$
一个行阶梯形矩阵称为行最简阶梯形矩阵，如果其非零行的第一个非零元素为 1 ，并且这些非零元素所在列的其他元素均为 0 .
$$

## 初等变换求逆矩阵

$$
\begin{pmatrix}
A & \vdots & E
\end{pmatrix}
\rightarrow 初等行变换 \rightarrow
\begin{pmatrix}
E & \vdots & A ^ {-1}
\end{pmatrix} .
$$

$$
\begin{pmatrix}
A \\
\cdots \\
E
\end{pmatrix}
\rightarrow 初等列变换 \rightarrow
\begin{pmatrix}
E \\
\cdots \\
A ^ {-1}
\end{pmatrix} .
$$

## 分块矩阵的逆

$$
\begin{pmatrix}
A & O \\
O & B
\end{pmatrix} ^ {-1}
=
\begin{pmatrix}
A ^ {-1} & O \\
O & B ^ {-1}
\end{pmatrix} ，
\begin{pmatrix}
O & A \\
B & O
\end{pmatrix} ^ {-1}
=
\begin{pmatrix}
O & B ^ {-1} \\
A ^ {-1} & O
\end{pmatrix} .
$$

## 经典例题

$$
设 A 是 3 阶可逆矩阵，将 A 的第 1 行和第 2 行互换后得到矩阵 B ，其中 A ^ {-1} =
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}
，求 B ^ {-1} .
\\
\because E_{12}A = B ，
\\
\therefore B ^ {-1} = {A ^ {-1}}{E_{12} ^ {-1}} = {A ^ {-1}}E_{12} ，
\\
\therefore B ^ {-1} =
\begin{pmatrix}
a_{12} & a_{11} & a_{13} \\
a_{22} & a_{21} & a_{23} \\
a_{32} & a_{31} & a_{33}
\end{pmatrix} .
$$

$$
设 A 是 3 阶矩阵，将 A 的第 1 列与第 2 列互换得到 B ，再将 B 的第 2 列加到第 3 列得到 C ，求满足 AQ = C 的可逆矩阵 Q .
\\
\because AE_{12} = A
\begin{pmatrix}
0 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{pmatrix}
= B ，
\\
\because BE_{23}(1) = B
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{pmatrix}
= C ，
\\
\therefore A{E_{12}}{E_{23}(1)} = A
\begin{pmatrix}
0 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{pmatrix}
= AQ = C ，
\\
\therefore Q =
\begin{pmatrix}
0 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{pmatrix}
\begin{pmatrix}
0 & 1 & 1 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{pmatrix} .
$$

$$
设 A =
\begin{pmatrix}
0 & 2 & -1 \\
1 & 1 & 2 \\
-1 & -1 & -1
\end{pmatrix}
，求 A ^ {-1} .
\\
\because
\begin{pmatrix}
A & \vdots & E
\end{pmatrix}
=
\begin{pmatrix}
0 & 2 & -1 & \vdots & 1 & 0 & 0 \\
1 & 1 & 2 & \vdots & 0 & 1 & 0 \\
-1 & -1 & -1 & \vdots & 0 & 0 & 1
\end{pmatrix}
=
\begin{pmatrix}
0 & 2 & -1 & \vdots & 1 & 0 & 0 \\
1 & 1 & 2 & \vdots & 0 & 1 & 0 \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 1 & 2 & \vdots & 0 & 1 & 0 \\
0 & 2 & -1 & \vdots & 1 & 0 & 0 \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 5 & 0 & \vdots & 2 & 1 & 0 \\
0 & 2 & -1 & \vdots & 1 & 0 & 0 \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix}
\\
=
\begin{pmatrix}
1 & 5 & 0 & \vdots & 2 & 1 & 0 \\
0 & 2 & 0 & \vdots & 1 & 1 & 1 \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 5 & 0 & \vdots & 2 & 1 & 0 \\
0 & 1 & 0 & \vdots & \frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 & 0 & \vdots & -\frac{1}{2} & -\frac{3}{2} & -\frac{5}{2} \\
0 & 1 & 0 & \vdots & \frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix} ，
\\
\therefore A ^ {-1} =
\begin{pmatrix}
1 & 0 & 0 & \vdots & -\frac{1}{2} & -\frac{3}{2} & -\frac{5}{2} \\
0 & 1 & 0 & \vdots & \frac{1}{2} & \frac{1}{2} & \frac{1}{2} \\
0 & 0 & 1 & \vdots & 0 & 1 & 1
\end{pmatrix} .
$$



