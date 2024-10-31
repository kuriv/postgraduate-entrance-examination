# 等价无穷小转换

* [使用条件](#使用条件)
* [常用等价无穷小](#常用等价无穷小)
* [经典例题](#经典例题)


## 使用条件

$$
如果 \alpha \sim \alpha_1 ， \beta \sim \beta_1 ，则 \lim \frac{\alpha}{\beta} = \lim \frac{\alpha_1}{\beta} = \lim \frac{\alpha}{\beta_1} = \lim \frac{\alpha_1}{\beta_1} .
\\
如： \lim_{x \to 0} \frac{\sin{x}}{x} = \frac{x}{x} = 1 .
$$

$$
如果 \alpha \sim \alpha_1 ， \beta \sim \beta_1 ，且 \lim \frac{\alpha_1}{\beta_1} = A \neq 1 ，则 \alpha - \beta = \alpha_1 - \beta_1 .
\\
如果 \alpha \sim \alpha_1 ， \beta \sim \beta_1 ，且 \lim \frac{\alpha_1}{\beta_1} = A \neq -1 ，则 \alpha + \beta = \alpha_1 + \beta_1 .
$$

## 常用等价无穷小

$$
x \sim \sin{x} \sim \arcsin{x} \sim \tan{x} \sim \arctan{x} \sim e ^ x - 1 \sim \ln(x + 1) \sim \ln(x + \sqrt{x ^ 2 + 1}) ，
\\
(x + 1) ^ a - 1 \sim ax(a \neq 0) ， a ^ x - 1 \sim x\ln{a} ，
\\
x - \sin{x} \sim \frac{1}{6}x ^ 3 ， \arcsin{x} - x \sim \frac{1}{6}x ^ 3 ，
\\
1 - \cos{x} \sim \frac{1}{2}x ^ 2 ， \sec{x} - 1 \sim \frac{1}{2}x ^ 2 ， x - \ln(x + 1) \sim \frac{1}{2}x ^ 2 ， e ^ x - 1 - x \sim \frac{1}{2}x ^ 2 ，
\\
\tan{x} - x \sim \frac{1}{3}x ^ 3 ， x - \arctan{x} \sim \frac{1}{3}x ^ 3 ，
\\
\tan{x} - \sin{x} \sim \frac{1}{2}x ^ 3 .
$$

## 经典例题

$$
如： \lim_{x \to 0} \frac{x - \sin{x}}{x ^ 3} 不能使用 \sin{x} \sim x 替换，因为 \lim \frac{\alpha_1}{\beta_1} = \frac{x}{x} = 1 ，
\\
而是使用 x - \sin{x} \sim \frac{1}{6}x ^ 3 ，即 \lim_{x \to 0} \frac{x - \sin{x}}{x ^ 3} = \frac{\frac{1}{6}x ^ 3}{x ^ 3} = \frac{1}{6} .
$$



