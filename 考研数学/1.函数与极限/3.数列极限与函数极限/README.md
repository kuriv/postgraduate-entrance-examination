# 数列极限与函数极限

* [数列极限](#数列极限)
* [函数极限](#函数极限)
* [经典例题](#经典例题)


## 数列极限

$$
定义：对于数列 \{X_n\} ，如果存在常数 a ，对 \forall \epsilon \gt 0 ， \exists N_+ ，使得当 n \gt N 时，|X_n - a| \lt \epsilon 成立，则常数 a 是数列 \{X_n\} 的极限.
$$

## 函数极限

$$
对于函数 f(x) ，如果存在常数 A ，对 \forall \epsilon \gt 0 ， \exists \delta \gt 0 ，使得当 0 \lt |f(x) - A| \lt \delta 时，|f(x) - A| \lt \epsilon 成立，则常数 A 是函数 f(x) 当 x \to x_0 的极限.
$$


$$
对于函数 f(x) ，如果存在常数 A ，对 \forall \epsilon \gt 0， \exists X \gt 0 ，使得当 |x| \gt X 时，|f(x) - A | \lt \epsilon 成立，则常数 A 是函数 f(x) 当 x \to \infty 的极限.
$$

## 经典例题

$$
证明： \lim_{x\to\infty} \frac{1}{n ^ 2} = 0 .
\\
证明如下：|X_n - a| = |\frac{1}{n ^ 2} - 0| = \frac{1}{n ^ 2} ，
\\
\because 要使 |X_n - a| \lt \epsilon ，即 \frac{1}{n ^ 2} \lt \epsilon ，
\\
\therefore n \gt \frac{1}{\sqrt{\epsilon}} ，
\\
\therefore \forall \epsilon \gt 0 ， \exists N_+ = \lfloor\frac{1}{\sqrt{\epsilon}}\rfloor ，当 n \gt N 时，|X_n - a| = |\frac{1}{n ^ 2} - 0| \lt \epsilon ，
\\
即 \lim_{x\to\infty} \frac{1}{n ^ 2} = 0 .
$$

$$
证明： \lim_{x\to\infty} \frac{3n + 1}{2n + 1} = \frac{3}{2} .
\\
证明如下：|X_n - a| = |\frac{3n + 1}{2n + 1} - \frac{3}{2}| = |\frac{2(3n + 1)}{2(2n + 1)} - \frac{3(2n + 1)}{2(2n + 1)}| = |\frac{-1}{4n + 2}| = \frac{1}{4n + 2} \lt \frac{1}{4n} ，
\\
\because 要使 |X_n - a| \lt \epsilon ，即 \frac{1}{4n} \lt \epsilon ，
\\
\therefore n \gt \frac{1}{4{\epsilon}} ，
\\
\therefore \forall \epsilon \gt 0 ， \exists N_+ = \lfloor\frac{1}{4{\epsilon}}\rfloor ，当 n \gt N 时，|X_n - a| = |\frac{3n + 1}{2n + 1} - \frac{3}{2}| \lt \epsilon ，
\\
即 \lim_{x\to\infty} \frac{3n + 1}{2n + 1} = \frac{3}{2} .
$$


$$
证明： \lim_{x\to3} (3x - 1) = 8 .
\\
证明如下：|f(x) - A| = |(3x - 1) - 8| = |3x - 9| = 3|x - 3| ，
\\
\because 要使 |f(x) - A| \lt \epsilon ，即 3|x - 3| \lt \epsilon ，
\\
\therefore |x - 3| \lt \frac{\epsilon}{3} ，
\\
\therefore \forall \epsilon \gt 0 ， \exists \delta = \frac{\epsilon}{3} ，当 0 \lt |x - 3| \lt \delta， |f(x) - A| = |(3x - 1) - 8| \lt \epsilon ，
\\
即 \lim_{x\to3} (3x - 1) = 8 .
$$

$$
证明： \lim_{x\to\infty} \frac{1 + x ^ 3}{2x ^ 3} = \frac{1}{2} .
\\
证明如下： |f(x) - A| = |\frac{1 + x ^ 3}{2x ^ 3} - \frac{1}{2}| = |\frac{1 + x ^ 3}{2x ^ 3} - \frac{x ^ 3}{2x ^ 3}| = |\frac{1}{2x ^ 3}| ，
\\
\because 要使|f(x) - A| \lt \epsilon ， 即 |\frac{1}{2x ^ 3}| \lt \epsilon ，
\\
\therefore |x ^ 3| \gt \frac{1}{2\epsilon} ， |x| \gt \frac{1}{\sqrt[3]{2\epsilon}} ，
\\
\therefore \forall \epsilon \gt 0 ， \exists X = \frac{1}{\sqrt[3]{2\epsilon}} ，当 |x| \gt X 时， |f(x) - A| = |\frac{1 + x ^ 3}{2x ^ 3} - \frac{1}{2}| \lt \epsilon ，
\\
即 \lim_{x\to\infty} \frac{1 + x ^ 3}{2x ^ 3} = \frac{1}{2}.
$$



