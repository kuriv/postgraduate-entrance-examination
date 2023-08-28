# 积分法则

* [有理运算法则](#有理运算法则)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)
  * [例题四](#例题四)
  * [例题五]


## 有理运算法则

$$
\int[f(x) \pm g(x)]dx = \int{f(x)}dx \pm \int{g(x)}dx
\\
\int{{kf(x)}dx} = k\int{fx}dx
$$

## 经典例题

### 例题一

$$
求 \int{\sqrt{x}(x ^ 2 - 5)}dx .
\\
\int{\sqrt{x}(x ^ 2 - 5)}dx = \int{x ^ {\frac{1}{2}}(x ^ 2 - 5)}dx = \int{x ^ {\frac{5}{2}} - 5x ^ {\frac{1}{2}}}dx = \int{x ^ {\frac{5}{2}}}dx - 5\int{x ^ {\frac{1}{2}}}dx = \frac{2}{7}x ^ {\frac{7}{2}} - 5 \cdot \frac{2}{3}x ^ {\frac{3}{2}} + C = \frac{2}{7}x ^ 3\sqrt{x} - \frac{10}{3}x\sqrt{x} + C .
$$

### 例题二

$$
求 \int{\frac{(x - 1) ^ 3}{x ^ 2}}dx .
\\
\int{\frac{(x - 1) ^ 3}{x ^ 2}}dx = \int{\frac{x ^ 3 - 3x ^ 2 + 3x - 1}{x ^ 2}}dx = \int{(x - 3 + \frac{3}{x} - \frac{1}{x ^ 2})}dx = \int{x}dx - \int{3}dx + \int{\frac{3}{x}}dx - \int{\frac{1}{x ^ 2}}dx
\\
= \frac{1}{2}x ^ 2 - 3x + 3\ln ^ {|x|} + \frac{1}{x} + C .
$$

### 例题三

$$
求 \int{{2 ^ x}{e ^ x}}dx .
\\
\int{{2 ^ x}{e ^ x}}dx = \int{(2e) ^ x}dx = \frac{(2e) ^ x}{\ln ^ {2e}} + C = \frac{{2 ^ x}{e ^ x}}{\ln ^ 2 + \ln ^ e} + C = \frac{{2 ^ x}{e ^ x}}{\ln ^ 2 + 1} + C .
$$

### 例题四

$$
求 \int{(\tan{x}) ^ 2}dx .
\\
\int{(\tan{x}) ^ 2}dx = \int{((\sec{x}) ^ 2 -1)}dx = \int{(\sec{x}) ^ 2}dx - \int{1}dx = \tan{x} - x + C .
$$

### 例题五

