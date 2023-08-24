# 零散知识点

* [因式分解](#因式分解)
* [指数幂](#指数幂)
  * [整数指数幂](#整数指数幂)
  * [分数指数幂](#分数指数幂)
* [对数](#对数)
* [绝对值比较](#绝对值比较)
* [均值不等式](#均值不等式)
* [根号运算](#根号运算)
* [对数运算](#对数运算)
* [反函数求解](#反函数求解)
* [排列组合公式](#排列组合公式)
  * [排列公式](#排列公式)
  * [组合公式](#组合公式)
* [渐近线](#渐近线)
  * [铅直渐近线](#铅直渐近线)
  * [水平渐近线](#水平渐近线)
  * [斜渐近线](#斜渐近线)



## 因式分解

$$
\frac{1 - x ^ 3}{1 - x} = \frac{(1 - x)(1 + x + x ^ 2)}{1 - x} = 1 + x + x ^ 2
\\
\frac{x ^ 3 - 1}{x - 1} = \frac{(x - 1)(x ^ 2 + x + 1)}{x - 1} = x ^ 2 + x + 1
$$

## 指数幂

### 整数指数幂

$$
2 ^ 2 = 4
\\
2 ^ 3 = 8
$$

$$
2 ^ {-2} = \frac{1}{2 ^ 2}
\\
2 ^ {-3} = \frac{1}{2 ^ 3}
$$

### 分数指数幂

$$
4 ^ \frac{1}{2} = \sqrt[2]{4} = 2
\\
8 ^ \frac{1}{3} = \sqrt[3]{8} = 2
\\
8 ^ \frac{2}{3} = (8 ^ 2) ^ \frac{1}{3} = \sqrt[3]{8 ^ 2} = 4
$$

$$
4 ^ {-\frac{1}{2}} = \frac{1}{\sqrt[2]{4}} = \frac{1}{2}
\\
8 ^ {-\frac{1}{3}} = \frac{1}{\sqrt[3]{8}} = \frac{1}{2}
\\
8 ^ {-\frac{2}{3}} = \frac{1}{(8 ^ 2) ^ \frac{1}{3}} = \frac{1}{\sqrt[3]{8 ^ 2}} = \frac{1}{4}
$$

## 对数

$$
假设 a ^ x = N（a > 0 ， a \neq 1 ; N > 0） ， 则 x = \log_a^{N} （a > 0 ， a \neq 1 ; N > 0）
$$

## 绝对值比较

$$
||x| + |y|| \ge |x + y|
\\
|x - y| \ge ||x| - |y||
$$

## 均值不等式

$$
a ^ 2 + b ^ 2 \ge 2ab
\\
a + b \ge 2\sqrt{ab}
\\
a ^ 2 + b ^ 2 + c ^ 2 \ge \frac{(a + b + c) ^ 2}{3}
\\
a + b + c \ge 3\sqrt[3]{abc}
$$

## 根号运算

$$
\sqrt{4} \cdot \sqrt{9} = \sqrt{4 \cdot 9} = 6
\\
\sqrt{16} \div \sqrt{4} = \sqrt{16 \div 4} = 2
$$

## 对数运算

$$
\log_a^{x} + \log_a^{y} = \log_a^{xy}
\\
\log_a^{x} - \log_a^{y} = \log_a^{\frac{x}{y}}
\\
\log_a^{x ^ y} = y\log_a^{x}
\\
\ln^{x} + \ln^{y} = \ln^{xy}
\\
\ln^{x} - \ln^{y} = \ln^{\frac{x}{y}}
\\
\ln^{x ^ y} = y\ln^{x}
$$

## 反函数求解

$$
y = 3x - 1 的反函数为 y = \frac{x + 1}{3}
\\
y = \sqrt{x} + 1 的反函数为 y = (x - 1) ^ 2
\\
y = 3 ^ {x - 1} + 2 的反函数为 \log_3^{x - 2} + 1
\\
y = \log_2^{x + 4} 的反函数为 y = 2 ^ x - 4
$$

## 排列组合公式

### 排列公式

$$
{A_6 ^ 2} = 6 \times 5 = 30
\\
{A_5 ^ 3} = 5 \times 4 \times 3 = 60
\\
{A_8 ^ 8} = 8!
$$

### 组合公式

$$
{C_6 ^ 2} = \frac{6 \times 5}{1 \times 2} = 15
\\
{C_5 ^ 3} = \frac{5 \times 4 \times 3}{1 \times 2 \times 3} = 10
\\
{C_5 ^ 3} = {C_5 ^ 2}
\\
{C_n ^ n} = {C_n ^ 0} = 1
$$

## 渐近线

### 铅直渐近线

$$
如果 \lim_{x \to x_0}f(x) = \infty ，则 x = x_0 为 f(x) 的铅直渐近线.
\\
如： x = 0 是 y = \frac{1}{x} 的铅直渐近线， x = k\pi + \frac{\pi}{2} （k \in Z） 是 y = tanx 的铅直渐近线.
$$

### 水平渐近线

$$
如果 \lim_{x \to \infty}f(x) = A ，则 y = A 为 f(x) 的水平渐近线.
\\
如： y = 0 是 y = e ^ x 的水平渐近线.
$$

### 斜渐近线

$$
如果存在常数 a 、 b ，使得 \lim_{x \to \infty}[f(x) - ax - b] = 0 ，则 y = ax + b 为 f(x) 的斜渐近线.
\\
其中： a = \lim_{x \to \infty}\frac{f(x)}{x} ， b = \lim_{x \to \infty}[f(x) - ax] .
\\
如：求 f(x) = \frac{2x ^ 3}{x ^ 2 - 3x + 2} 的斜渐近线.
\\
\because \lim_{x \to \infty}\frac{f(x)}{x} = \lim_{x \to \infty}\frac{\frac{2x ^ 3}{x ^ 2 - 3x + 2}}{x} = \lim_{x \to \infty}\frac{2x ^ 2}{x ^ 2 - 3x + 2} = 2 ，
\\
\because \lim_{x \to \infty}[f(x) - ax] = \lim_{x \to \infty}[\frac{2x ^ 3}{x ^ 2 - 3x + 2} - 2x] = \lim_{x \to \infty}\frac{2x ^ 3 - 2x ^ 3 + 6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = \lim_{x \to \infty}\frac{6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = 6 ，
\\
\therefore y = 2x + 6 是 \frac{2x ^ 3}{x ^ 2 - 3x + 2} 的斜渐近线.
$$



