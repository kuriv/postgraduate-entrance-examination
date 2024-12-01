# 矩阵的相似

* [定理内容](#定理内容)
* [相似性质](#相似性质)
* [经典例题](#经典例题)

## 定理内容

$$
设 A ， B 是两个 n 阶方阵，若存在 n 阶可逆矩阵 P ，使得 {P ^ {-1}}AP = B ，则称 A 相似于 B ，记作 A \sim B .
$$

## 相似性质

$$
若 A \sim B ，则
\\
|A| = |B| .
\\
r(A) = r(B) .
\\
tr(A) = tr(B) .
\\
\lambda_A = \lambda_B (或 |\lambda{E} - A| = |\lambda{E} - B|) .
\\
r(\lambda{E} - A) = r(\lambda{E} - B) .
\\
A ， B 的各阶主子式之和分别相等.
$$

$$
若 A \sim B ，则 A ^ k \sim B ^ k ， f(A) \sim f(B) (其中 f(x) 是多项式) .
\\
若 A \sim B ，且 A 可逆，则 A ^ {-1} \sim B ^ {-1} ， f(A ^ {-1}) \sim f(B ^ {-1}) (其中 f(x) 是多项式) .
\\
若 A \sim B ，则 A ^ {*} \sim B ^ {*} .
\\
若 A \sim B ，则 A ^ {T} \sim B ^ {T} .
\\
若 A \sim C ， B \sim D ，则
\begin{pmatrix}
A & O \\
O & B
\end{pmatrix}
\sim
\begin{pmatrix}
C & O \\
O & D
\end{pmatrix} .
$$

## 经典例题

$$
如：已知 A =
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 1 \\
0 & 1 & a
\end{pmatrix}
， B =
\begin{pmatrix}
2 \\
& b & \\
& & -1
\end{pmatrix}
，且 A \sim B ，求 a ， b .
\\
\because A \sim B \Leftarrow\Rightarrow |A| = |B| \Leftarrow\Rightarrow -2 = -2b ，
\\
\therefore b = 1 ，
\\
\because A \sim B \Leftarrow\Rightarrow tr(A) = tr(B) \Leftarrow\Rightarrow 2 + a = 1 + b ，
\\
\therefore a = 0 .
$$



