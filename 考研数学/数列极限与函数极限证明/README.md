# 数列极限与函数极限证明

* [数列极限](#数列极限)
* [函数极限](#函数极限)

## 数列极限

$$
定义：对于数列 \{X_n\} ，如果存在常数 a ，对 \forall\epsilon > 0 ， \exists 正整数 N ，使得当 n > N 时，|X_n - a| < \epsilon 成立，则常数 a 是数列 \{X_n\} 的极限。
$$


$$
证明一 \lim_{x\to\infty} \frac{1}{n ^ 2} = 0
$$

$$
证明一如下：|X_n - a| = |\frac{1}{n ^ 2} - 0| = \frac{1}{n ^ 2}
\\
\because 要使 |X_n - a| < \epsilon ，即 \frac{1}{n ^ 2} < \epsilon，
\\
\therefore n > \frac{1}{\sqrt{\epsilon}}，
\\
\therefore \forall\epsilon > 0 ， \exists正整数 N = \lfloor\frac{1}{\sqrt{\epsilon}}\rfloor ， 当 n > N 时，|X_n - a| = |\frac{1}{n ^ 2} - 0| < \epsilon，
\\
即 \lim_{x\to\infty} \frac{1}{n ^ 2} = 0
$$

$$
证明二 \lim_{x\to\infty} \frac{3n + 1}{2n + 1} = \frac{3}{2}
$$

$$
证明二如下：|X_n - a| = |\frac{3n + 1}{2n + 1} - \frac{3}{2}| = |\frac{2(3n + 1)}{2(2n + 1)} - \frac{3(2n + 1)}{2(2n + 1)}| = |\frac{-1}{4n + 2}| = \frac{1}{4n + 2} < \frac{1}{4n}
\\
\because 要使 |X_n - a| < \epsilon ，即 \frac{1}{4n} < \epsilon，
\\
\therefore n > \frac{1}{4{\epsilon}}，
\\
\therefore \forall\epsilon > 0 ， \exists正整数 N = \lfloor\frac{1}{4{\epsilon}}\rfloor ， 当 n > N 时，|X_n - a| = |\frac{3n + 1}{2n + 1} - \frac{3}{2}| < \epsilon，
\\
即 \lim_{x\to\infty} \frac{3n + 1}{2n + 1} = \frac{3}{2}
$$

## 函数极限

$$
定义一：对于函数 f(x) ，如果存在常数 A ，对 \forall\epsilon > 0 ， \exists\delta > 0 ，使得当 0 < |f(x) - A| < \delta 时，|f(x) - A| < \epsilon 成立，则常数 A 是函数 f(x) 当 x \rightarrow x_0 的极限。
$$

$$
证明三
$$

$$
证明三如下：
$$




$$
定义二：对于函数 f(x) ，如果存在常数 A ，对 \forall\epsilon > 0， \exists X > 0 ，使得当 |x| > X 时，|f(x) - A |< \epsilon 成立，则常数 A 是函数 f(x) 当 x \rightarrow \infty 的极限。
$$




