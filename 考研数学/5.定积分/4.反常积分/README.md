# 反常积分

* [无穷区间](#无穷区间)
* [无界函数](#无界函数)
* [敛散性判别](#敛散性判别)
* [两个重要结论](#两个重要结论)

## 无穷区间

$$
设 F(x) 是 f(x) 在相应区间上的一个原函数，
\\
\int_{a} ^ {+\infty}{f(x)dx} = \lim_{x \to +\infty} F(x) - F(a) ，若极限存在，则反常积分收敛，否则发散.
\\
\int_{-\infty} ^ {b}{f(x)dx} = F(b) - \lim_{x \to -\infty} F(x) ，若极限存在，则反常积分收敛，否则发散.
\\
\int_{-\infty} ^ {+\infty}{f(x)dx} = \int_{x_0} ^ {+\infty}{f(x)dx} + \int_{-\infty} ^ {x_0}{f(x)dx} ，若右端两个积分都收敛，则反常积分收敛，否则称发散.
$$

## 无界函数

$$
设 F(x) 是 f(x) 在相应区间上的一个原函数， x_0 为 f(x) 的瑕点，
\\
当 x = a 是唯一瑕点， \int_{a} ^ {b}{f(x)dx} = F(b) - \lim_{x \to a+} F(x) ，若极限存在，则反常积分收敛，否则发散.
\\
当 x = b 是唯一瑕点， \int_{a} ^ {b}{f(x)dx} = \lim_{x \to b-} F(x) - F(a) ，若极限存在，则反常积分收敛，否则发散.
\\
当 x = c \in (a , b) 是唯一瑕点， \int_{a} ^ {b}{f(x)dx} = \int_{c} ^ {b}{f(x)dx} + \int_{a} ^ {c}{f(x)dx} ，若右端两个积分都收敛，则反常积分收敛，否则发散.
$$

## 敛散性判别

$$
设函数 f(x) ， g(x) 在区间 [a , +\infty) 上连续，且 0 \le f(x) \le g(x) ，
\\
当 \int_{a} ^ {+\infty}{g(x)dx} 收敛时， \int_{a} ^ {+\infty}{f(x)dx} 收敛.
\\
当 \int_{a} ^ {+\infty}{f(x)dx} 发散时， \int_{a} ^ {+\infty}{f(x)dx} 发散.
$$

$$
设函数 f(x) ， g(x) 在区间 [a , +\infty) 上连续，且 f(x) \ge 0 ， g(x) \gt 0 ， \lim_{x \to +\infty} \frac{f(x)}{g(x)} = A ，
\\
当 A \neq 0 且 A \neq \infty 时， \int_{a} ^ {+\infty}{f(x)dx} 与 \int_{a} ^ {+\infty}{g(x)dx} 有相同的敛散性.
\\
当 A = 0 时，若 \int_{a} ^ {+\infty}{g(x)dx} 收敛，则 \int_{a} ^ {+\infty}{f(x)dx} 也收敛.
\\
当 A = \infty 时，若 \int_{a} ^ {+\infty}{g(x)dx} 发散，则 \int_{a} ^ {+\infty}{f(x)dx} 也发散.
$$

## 两个重要结论

$$
\int_{0} ^ {1}{\frac{1}{x ^ p}dx}
\begin{cases}
收敛， 0 \lt p \lt 1 \\
发散， p \ge 1 .
\end{cases}
\\
\int_{1} ^ {+\infty}{\frac{1}{x ^ p}dx}
\begin{cases}
收敛， p \gt 1 \\
发散， p \le 1 .
\end{cases}
$$



