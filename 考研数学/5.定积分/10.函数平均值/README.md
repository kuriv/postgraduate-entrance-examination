# 函数平均值

* [基本公式](#基本公式)
* [经典例题](#经典例题)

## 基本公式

$$
设 x \in [a , b] ，函数 y(x) 在 [a , b] 上的平均值为 \bar{y} = \frac{1}{b - a}\int_{a} ^ {b}{y(x)}dx .
$$

## 经典例题

$$
如：设 f(x) 连续，且 f(x + 2) - f(x) = x ， \int_{0} ^ {2}{f(x)}dx = 0 ，求 f(x) 在 [1 , 3] 上的平均值.
\\
令 F(x) = \int_{x} ^ {x + 2}{f(t)}dt ，则 F ^ {\prime} (x) = f(x + 2) - f(x) = x ， F(x) = \int{x}dx = \frac{1}{2}x ^ 2 + C ，
\\
\because F(0) = \int_{0} ^ {2}{f(x)}dx = 0 ，
\\
\therefore C = 0 ， F(x) = \frac{1}{2}x ^ 2 ，
\\
\therefore \bar{f(x)} = \frac{1}{b - a}\int_{a} ^ {b}{f(x)}dx = \frac{1}{3 - 1}\int_{1} ^ {3}{f(x)}dx = \frac{1}{2}F(1) = \frac{1}{4} .
$$



