# 夹逼准则

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
若存在 N ，当 n \gt N 时， {x_n} \le {y_n} \le {z_n} ，且 \lim_{n \to \infty} x_n = \lim_{n \to \infty} z_n = a ， 则 \lim_{n \to \infty} y_n = a .
$$

## 经典例题

$$
如：求 \lim_{n \to \infty} (\frac{n}{n ^ 2 + 1} + \frac{n}{n ^ 2 + 2} + ... + \frac{n}{n ^ 2 + n}) 的极限.
\\
\because \ \frac{n ^ 2}{n ^ 2 + n} \le (\frac{n}{n ^ 2 + 1} + \frac{n}{n ^ 2 + 2} + ... + \frac{n}{n ^ 2 + n}) \le \frac{n ^ 2}{n ^ 2 + 1} ，
\\
\because \lim_{n \to \infty} \frac{n ^ 2}{n ^ 2 + n} = \lim_{n \to \infty}\frac{n ^ 2}{n ^ 2 + 1} = 1 ，
\\
\therefore \lim_{n \to \infty} (\frac{n}{n ^ 2 + 1} + \frac{n}{n ^ 2 + 2} + ... + \frac{n}{n ^ 2 + n}) = 1 .
$$



