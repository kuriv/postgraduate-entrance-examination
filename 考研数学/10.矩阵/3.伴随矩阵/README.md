# 伴随矩阵

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
将行列式 |A| 的 n ^ 2 个元素的代数余子式按如下形式排成的矩阵称为 A 的伴随矩阵，记作 A ^ {*} ，即
\\
A ^ {*} =
\begin{pmatrix}
A_{11} & A_{21} & \cdots & A_{n1} \\
A_{12} & A_{22} & \cdots & A_{n2} \\
\vdots & \vdots & \vdots & \vdots \\
A_{1n} & A_{2n} & \cdots & A_{mn}
\end{pmatrix} .
$$

$$
A{A ^ {*}} = {A ^ {*}}A = |A|E .
\\
|A ^ {*}| = |A| ^ {n - 1} (A{A ^ {*}} = |A| \Rightarrow |A{A ^ {*}}| = ||A|| \Rightarrow |A||A ^ {*}| = |A| ^ {n} \Rightarrow |A ^ {*}| = |A| ^ {n - 1}) .
\\
A ^ {*} = {A ^ {-1}}|A| (A{A ^ {*}} = |A| \Rightarrow {A ^ {-1}}A{A ^ {*}} = {A ^ {-1}}|A| \Rightarrow A ^ {*} = {A ^ {-1}}|A|) .
\\
A ^ {-1} = \frac{1}{|A|}{A ^ {*}} (A ^ {*} = {A ^ {-1}}|A| \Rightarrow A ^ {-1} = \frac{1}{|A|}{A ^ {*}}) .
\\
A = |A|(A ^ {*}) ^ {-1} (|A| = |A| \Rightarrow A{A ^ {*}} = |A| \Rightarrow A{A ^ {*}} = |A|(A ^ {*}) ^ {-1}{A ^ {*}} \Rightarrow A = |A|(A ^ {*}) ^ {-1}) .
\\
(kA)(kA) ^ {*} = |kA|E (A{A ^ {*}} = |A|E \Rightarrow (kA)(kA) ^ {*} = |kA|E) .
\\
A ^ {T}{(A ^ {T}) ^ {*}} = |A ^ {T}|E (A{A ^ {*}} = |A|E \Rightarrow A ^ {T}{(A ^ {T}) ^ {*}} = |A ^ {T}|E) .
\\
A ^ {-1}{(A ^ {-1}) ^ {*}} = |A ^ {-1}|E (A{A ^ {*}} = |A|E \Rightarrow A ^ {-1}{(A ^ {-1}) ^ {*}} = |A ^ {-1}|E) .
\\
A ^ {*}(A ^ {*}) ^ {*} = |A ^ {*}|E (A{A ^ {*}} = |A|E \Rightarrow A ^ {*}(A ^ {*}) ^ {*} = |A ^ {*}|E) .
\\
(A ^ {T}) ^ {*} = (A ^ {*}) ^ {T} .
\\
(A ^ {-1}) ^ {*} = (A ^ {*}) ^ {-1} .
\\
(AB) ^ {*} = {B ^ {*}}{A ^ {*}} .
\\
(A ^ {*}) ^ {*} = {|A| ^ {n - 2}}A ((A ^ {*}) ^ {*}{A ^ {*}} = {|A| ^ {n - 2}}A{A ^ {*}} \Rightarrow |A ^ {*}| = {|A| ^ {n - 2}}|A| \Rightarrow |A ^ {*}| = |A| ^ {n - 1}) .
$$

## 经典例题

$$
求矩阵 A =
\begin{pmatrix}
1 & 0 & 1 \\
2 & 1 & 0 \\
-3 & 2 & -5
\end{pmatrix}
的逆矩阵.
\\
\because |A| =
\begin{vmatrix}
1 & 0 & 1 \\
2 & 1 & 0 \\
-3 & 2 & -5
\end{vmatrix}
= 2 \neq 0 ，知 A 可逆，
\\
\therefore A ^ {*} =
\begin{pmatrix}
-5 & 2 & -1 \\
10 & -2 & 2 \\
7 & -2 & 1
\end{pmatrix} ，
\\\
\therefore A ^ {-1} = \frac{1}{|A|}A ^ {*} = \frac{1}{2}
\begin{pmatrix}
-5 & 2 & -1 \\
10 & -2 & 2 \\
7 & -2 & 1
\end{pmatrix}
=
\begin{pmatrix}
-\frac{5}{2} & 1 & -\frac{1}{2} \\
5 & -1 & 1 \\
\frac{7}{2} & -1 & \frac{1}{2}
\end{pmatrix} .
$$

$$
设 A =
\begin{pmatrix}
1 & 2 & 0 \\
2 & 2 & 0 \\
3 & 4 & 5
\end{pmatrix}
， A ^ {*} 是 A 的伴随矩阵，求 (A ^ {*}) ^ {-1} .
\\
\because A ^ {*} = |A|{A ^ {-1}} ，
\\
\therefore (A ^ {*}) ^ {-1} = (|A|{A ^ {-1}}) ^ {-1} = {|A| ^ {-1}}A = -\frac{1}{10}
\begin{pmatrix}
1 & 2 & 0 \\
2 & 2 & 0 \\
3 & 4 & 5
\end{pmatrix} .
$$



