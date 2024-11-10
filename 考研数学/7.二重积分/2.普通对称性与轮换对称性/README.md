# 普通对称性与轮换对称性

* [普通对称性](#普通对称性)
* [轮换对称性](#轮换对称性)
* [经典例题](#经典例题)

## 普通对称性

$$
若 D 关于 y 轴对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(-x , y) ，
\\
0 ， f(x , y) = -f(-x , y) .
\end{cases}
$$

$$
若 D 关于 x = a (a \neq 0) 对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(2a - x , y) ，
\\
0 ， f(x , y) = -f(2a - x , y) .
\end{cases}
$$

$$
若 D 关于 x 轴对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(x , -y) ，
\\
0 ， f(x , y) = -f(x , -y) .
\end{cases}
$$

$$
若 D 关于 y = a (a \neq 0) 对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(x , 2a - y) ，
\\
0 ， f(x , y) = -f(x , 2a - y) .
\end{cases}
$$

$$
若 D 关于原点对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(-x , -y) ，
\\
0 ， f(x , y) = -f(-x , -y) .
\end{cases}
$$

$$
若 D 关于 y = x 对称，则 \iint_D{f(x , y)}d\sigma =
\begin{cases}
2\iint_{D_1}{f(x , y)}d\sigma ， f(x , y) = f(y , x) ，
\\
0 ， f(x , y) = -f(y , x) .
\end{cases}
$$

## 轮换对称性

$$
在直角坐标系下，若把 x 和 y 对调后，区域 D 不变（或区域 D 关于 y = x 对称），则 \iint_D{f(x , y)}d\sigma = \iint_D{f(y , x)}d\sigma .
\\
若 f(x , y) + f(y , x) = a ，则 I = \frac{1}{2}\iint_D{[f(x , y) + f(y , x)]}dxdy = \frac{1}{2}\iint_D{a}dxdy = \frac{a}{2}S_D .
$$

## 经典例题

$$
如：设 f(x) = \iint_{D(x)}{\frac{v\ln{\sqrt{u ^ 2 + v ^ 2}}}{u + v}}dudv ， D(x) = \{(u , v)|\frac{1}{4} \le u ^ 2 + v ^ 2 \le x ^ 2 ， u \gt 0 ， v \gt 0\} ，求 f(x) .
\\
由轮换对称性可得， f(x) = \iint_{D(x)}{\frac{v\ln{\sqrt{u ^ 2 + v ^ 2}}}{u + v}}dudv = \iint_{D(x)}{\frac{u\ln{\sqrt{u ^ 2 + v ^ 2}}}{u + v}}dudv = \frac{1}{2}\iint_{D(x)}{\ln{\sqrt{u ^ 2 + v ^ 2}}}dudv ，
\\
\therefore f(x) = \frac{1}{4}\iint_{D(x)}{\ln{(u ^ 2 + v ^ 2)}}dudv .
$$



