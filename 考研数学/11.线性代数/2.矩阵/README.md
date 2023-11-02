# 矩阵

* [定理内容](#定理内容)
* [特殊矩阵](#特殊矩阵)
* [矩阵的运算及性质](#矩阵的运算及性质)
* [矩阵的秩](#矩阵的秩)
* [矩阵等价](#矩阵等价)

## 定理内容

$$
定义： A = \begin{bmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{m1} \ a_{m2} \ \cdots \ a_{mn}
\end{bmatrix}
称为 m \times n 矩阵，记为 A = (a_{ij})_{m \times n} .
$$

$$
定义：若矩阵 A ， B 的行数和列数相同，称矩阵 A ， B 为同型矩阵.
\\
若矩阵 A ， B 的每一行或列的元素都分别相等，则称矩阵 A ， B 相等，记为 A = B .
$$

$$
定义：令 A = \begin{bmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{bmatrix} 为 n 阶矩阵，
\\
\ 取 |A| = \begin{vmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{vmatrix} ，记 |A| 中的 a_{ij} 的余子式为 M_{ij} ，代数余子式为 A_{ij} ，
\\
称 A ^ * = \begin{bmatrix}
A_{11} \ A_{12} \ \cdots \ A_{1n}\\
A_{21} \ A_{22} \ \cdots \ A_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
A_{n1} \ A_{n2} \ \cdots \ A_{nn}
\end{bmatrix} 为矩阵 A 的伴随矩阵 .
$$

$$
定义：设 A 是 n 阶矩阵，若存在 n 阶矩阵 B ，使得 BA = E （或 AB = E），称矩阵 A 可逆，矩阵 B 为矩阵 A 的逆矩阵，记为 B = A ^ {-1} .
$$

## 特殊矩阵

$$
设 A = (a_{ij})_{m \times n} ，若 \forall{a_{ij}} = 0 ，称 A 为零矩阵，记为 A = O .
$$

$$
设 A = (a_{ij})_{m \times n} ，若 m = n ，称 A 为 n 阶方阵.
$$

$$
称 E = \begin{bmatrix}
1 \ \ \ \ 0 \ \ \ \ \cdots \ \ \ \ 0\\
0 \ \ \ \ 1 \ \ \ \ \cdots \ \ \ \ 0\\
0 \ \ \cdots \ \cdots \ \cdots\\
0 \ \ \ \ 0 \ \ \ \ \cdots \ \ \ \ 1
\end{bmatrix} 为单位矩阵，
称 \begin{bmatrix}
a \ \ \ \ 0 \ \ \ \ \cdots \ \ \ \ 0\\
0 \ \ \ \ a \ \ \ \ \cdots \ \ \ \ 0\\
0 \ \ \cdots \ \cdots \ \cdots\\
0 \ \ \ \ 0 \ \ \ \ \cdots \ \ \ \ a
\end{bmatrix} 为数量矩阵.
$$

$$
设 A = \begin{bmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{m1} \ a_{m2} \ \cdots \ a_{mn}
\end{bmatrix} ，称 \begin{bmatrix}
a_{11} \ a_{21} \ \cdots \ a_{m1}\\
a_{12} \ a_{22} \ \cdots \ a_{m2}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{1n} \ a_{2n} \ \cdots \ a_{mn}
\end{bmatrix} 为矩阵 A 的转置矩阵，记为 A ^ T .
\\
$$

$$
设 A = \begin{bmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{m1} \ a_{m2} \ \cdots \ a_{mn}
\end{bmatrix} ，若 a_{ij} = a_{ji} （i , j = 1 , 2 , \cdots , n）或 A ^ T = A ，称 A 为实对称矩阵.
$$

$$
设 A = \begin{bmatrix}
a_{11} \ a_{12} \ \cdots \ a_{1n}\\
a_{21} \ a_{22} \ \cdots \ a_{2n}\\
\cdots \ \cdots \ \cdots \ \cdots\\
a_{n1} \ a_{n2} \ \cdots \ a_{nn}
\end{bmatrix} ，若 A ^ TA = E ，称 A 为正交矩阵.
$$

## 矩阵的运算及性质

$$
A + B = B + A ， (A + B) + C = A + (B + C) .
$$

$$
两个矩阵相乘的规则是：两矩阵内标相同可乘，乘积而成的矩阵型由外标确定.
$$

$$
矩阵乘法不满足交换律，如 AB \neq BA .
$$

$$
由 A \neq O ， B \neq O 不一定能推出 AB \neq O ，同理，由 AB = AC 不一定能推出 B = C ，但若 A 可逆，则一定有 B = C .
$$

$$
(AB)C = A(BC) ， (k + l)A = kA + lA ， k(A + B) = kA + kB ， (A + B)C = AC + AC .
$$

$$
(AB) ^ * = B ^ *A ^ * ， AA ^ * = A ^ *A = |A|E ， (kA) ^ * = k ^ {n - 1}A ^ * .
$$

$$
(A ^ T) ^ T = A ， (kA) ^ T = kA ^ T ， (A \pm B) ^ T = A ^ T \pm B ^ T ， (AB) ^ T = B ^ TA ^ T ， (A ^ {-1}) ^ T = (A ^ T) ^ {-1} ， (A ^ T) ^ m = (A ^ m) ^ T ， (A ^ T) ^ * = (A ^ *) ^ T .
$$

$$
对调矩阵的两行（或列）、矩阵的某行（或列）乘以非零常数 k 、矩阵的某行（或列）的倍数加到另一行（或列），称为矩阵的三种初等变换.
$$

$$
(A ^ {-1}) ^ {-1} = A ， (kA) ^ {-1} = \frac{1}{k}A ^ {-1} ， (AB) ^ {-1} = A ^ {-1}B ^ {-1} ， (A ^ n) ^ {-1} = (A ^ {-1}) ^ n .
$$

$$
设 A ， B 分别为 m 和 n 阶可逆矩阵，则 \begin{bmatrix}
A \ O\\
O \ B
\end{bmatrix} ^ {-1} = \begin{bmatrix}
A ^ {-1} \ \ \ O\\
O \ \ \ \ B ^ {-1}
\end{bmatrix} ， \begin{bmatrix}
O \ A\\
B \ O
\end{bmatrix} ^ {-1} = \begin{bmatrix}
O \ \ \ \ A ^ {-1}\\
B ^ {-1} \ \ \ O
\end{bmatrix} .
$$

## 矩阵的秩

$$
定义：设 A 是 m \times n 矩阵，矩阵 A 中任取 r 行和 r 列按照原有次序排列，若至少有一个 r 阶子式不为零，但所有 r + 1 阶子式均为零，称 r 为矩阵 A 的秩，记为 r(A) = r .
$$

$$
矩阵的秩本质上为方程组中约束条件的个数，故对矩阵进行初等行变换阶梯化后非零行数即为矩阵的秩.
$$

$$
r(A) = 0 的充分必要条件是 A = O .
\\
r(A) \ge 1 的充分必要条件是 A \neq O .
\\
r(A) \ge 2 的充分必要条件是 A 至少两行不成比例.
$$

$$
r(A) = r(A ^ T) = r(A ^ TA) = r(AA ^ T) .
\\
r(A \pm B) \le r(A) \pm r(B) .
\\
r(AB) \le \min\{r(A) , r(B)\} .
\\
$$

## 矩阵等价

$$
定义：设 A 、 B 是两个同型矩阵，若 A 经过有限次初等变换化为 B ，称矩阵 A 与矩阵 B 等价.
$$



