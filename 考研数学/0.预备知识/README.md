# 预备知识

* [因式分解](#因式分解)
* [指数幂](#指数幂)
  * [整数指数幂](#整数指数幂)
  * [分数指数幂](#分数指数幂)
  * [对数指数幂](#对数指数幂)
* [数列](#数列)
  * [等差数列](#等差数列)
  * [等比数列](#等比数列)
* [绝对值比较](#绝对值比较)
* [均值不等式](#均值不等式)
* [根号运算](#根号运算)
* [对数运算](#对数运算)
* [反函数求解](#反函数求解)
* [排列组合公式](#排列组合公式)
  * [排列公式](#排列公式)
  * [组合公式](#组合公式)
* [函数性质](#函数性质)
  * [函数单调性](#函数单调性)
  * [函数奇偶性](#函数奇偶性)
  * [函数周期性](#函数周期性)
* [恒等式](#恒等式)


## 因式分解

$$
\frac{1 - x ^ 3}{1 - x} = \frac{(1 - x)(1 + x + x ^ 2)}{1 - x} = 1 + x + x ^ 2
\\
\frac{x ^ 3 - 1}{x - 1} = \frac{(x - 1)(x ^ 2 + x + 1)}{x - 1} = x ^ 2 + x + 1
$$

$$
a ^ 3 + b ^ 3 = (a + b)(a ^ 2 - ab + b ^ 2)
\\
a ^ 3 - b ^ 3 = (a - b)(a ^ 2 + ab + b ^ 2)
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

### 对数指数幂

$$
\log_a{\frac{1}{x}} = -\log_a{x}
$$

$$
e ^ {\ln{2}} = 2
$$

## 数列

### 等差数列

$$
a_n = a_1 + (n - 1)d
\\
S = \frac{n(a_1 + a_n)}{2}
$$

### 等比数列

$$
a_n = {a_1}{q ^ {n - 1}}
\\
S = \begin{cases}
{n}{a_1} , q = 1 ,
\\
\frac{a1(1 - q ^ n)}{1 - q} , q \neq 1 .
\end{cases}
$$

## 绝对值比较

$$
||x| + |y|| \ge |x + y|
\\
|x - y| \ge ||x| - |y||
\\
\frac{x ^ 2 + y ^ 2}{2} \ge |xy|
$$

## 均值不等式

$$
\frac{1}{x} \gt \ln{(1 + \frac{1}{x})} > \frac{1}{x + 1}
\\
\frac{a + b}{2} \ge \sqrt{ab}
\\
(\frac{{a + b}}{2}) ^ 2 \ge ab
\\
\frac{a + b + c}{3} \ge \sqrt[3]{abc}
\\
a ^ 2 + b ^ 2 \gt 2ab
\\
x - 1 \lt [x] \le x
\\
0 \lt a \lt x \lt b ， 0 \lt c \lt y \lt d ， 则 \frac{c}{b} \lt \frac{y}{x} \lt \frac{d}{a}
$$

## 根号运算

$$
\sqrt{4} \cdot \sqrt{9} = \sqrt{4 \cdot 9} = 6
\\
\sqrt{16} \div \sqrt{4} = \sqrt{16 \div 4} = 2
$$

## 对数运算

$$
\log_a{xy} = \log_a{x} + \log_a{y}
\\
\log_a{\frac{x}{y}} = \log_a{x} - \log_a{y}
\\
\ln{xy} = \ln{x} + \ln{y}
\\
\ln{\frac{x}{y}} = \ln{x} - \ln{y}
$$

## 反函数求解

$$
y = 3x - 1 \Rightarrow y = \frac{x + 1}{3}
\\
y = \sqrt{x} + 1 \Rightarrow y = (x - 1) ^ 2
\\
y = 3 ^ {x - 1} + 2 \Rightarrow \log_3{(x - 2)} + 1
\\
y = \log_2{(x + 4)} \Rightarrow y = 2 ^ x - 4
\\
y = \ln(x + \sqrt{x ^ 2 + 1}) \Rightarrow y = \frac{e ^ x - e ^ {-x}}{2}
$$

## 排列组合公式

### 排列公式

$$
{A_6 ^ 2} = 6 \times 5 = 30
\\
{A_5 ^ 3} = 5 \times 4 \times 3 = 60
\\
{A_n ^ n} = n!
\\
{A_n ^ 0} = 1
$$

### 组合公式

$$
{C_6 ^ 2} = \frac{6 \times 5}{1 \times 2} = 15
\\
{C_5 ^ 3} = \frac{5 \times 4 \times 3}{1 \times 2 \times 3} = 10
\\
{C_n ^ n} = {C_n ^ 0} = 1
$$

## 函数性质

### 函数单调性

$$
f(x) 是单调增函数 \Leftarrow\Rightarrow (x_1 - x_2)[f(x_1) - f(x_2)] \gt 0
\\
f(x) 是单调减函数 \Leftarrow\Rightarrow (x_1 - x_2)[f(x_1) - f(x_2)] \lt 0
$$

### 函数奇偶性

$$
奇函数乘以奇函数等于偶函数
\\
奇函数乘以偶函数等于奇函数
\\
偶函数乘以偶函数等于偶函数
$$

$$
f(x) + f(-x) 必是偶函数，如 \frac{e ^ x + e ^ {-x}}{2} ， \frac{1}{2 ^ x + 1} + \frac{1}{2}
\\
f(x) - f(-x) 必是奇函数，如 \frac{e ^ x - e ^ {-x}}{2} ， \frac{1}{2 ^ x + 1} - \frac{1}{2}
$$

$$
f[g(x)] (内偶则偶，内奇同外) \begin{cases}
奇[偶] \Rightarrow 偶，
\\
偶[偶] \Rightarrow 偶，
\\
非奇非偶[偶] \Rightarrow 偶，
\\
偶[奇] \Rightarrow 偶，
\\
奇[奇] \Rightarrow 奇
\end{cases}
$$

### 函数周期性

$$
若 g(x) 是周期函数，则复合函数 f[g(x)] 也是周期函数
\\
若 f(x) 是以 T 为周期的可导函数，则 f(x)\prime 也以 T 为周期
$$

## 恒等式

$$
1 ^ 2 + 2 ^ 2 + 3 ^ 3 + \cdots + n ^ n = \frac{n(n + 1)(2n + 1)}{6}
$$



