# 等价无穷小转换

* [使用条件](#使用条件)
* [常用的等价无穷小](#常用的等价无穷小)

## 使用条件

$$
如果 \alpha ～ \alpha_1 ， \beta ～ \beta_1 ，则 \lim\frac{\alpha}{\beta} = \lim\frac{\alpha_1}{\beta} = \lim\frac{\alpha}{\beta_1} = \lim\frac{\alpha_1}{\beta_1} .
\\
如： \lim_{x \to 0}\frac{sinx}{x} = \frac{x}{x} = 1 .
$$

$$
如果 \alpha ～ \alpha_1 ， \beta ～ \beta_1 ，且 \lim\frac{\alpha_1}{\beta_1} = A \neq 1 ，则 \alpha - \beta = \alpha_1 - \beta_1 .
\\
如果 \alpha ～ \alpha_1 ， \beta ～ \beta_1 ，且 \lim\frac{\alpha_1}{\beta_1} = A \neq -1 ，则 \alpha + \beta = \alpha_1 + \beta_1 .
\\
如： \lim_{x \to 0}\frac{x - sinx}{x ^ 3} 不能使用 sinx ～ x 替换，因为 \lim\frac{\alpha_1}{\beta_1} = \frac{x}{x} = 1 ，
\\
而是使用 x - sinx ～ \frac{1}{6}x ^ 3 ，即 \lim_{x \to 0}\frac{x - sinx}{x ^ 3} = \frac{\frac{1}{6}x ^ 3}{x ^ 3} = \frac{1}{6} .
$$

## 常用的等价无穷小

$$
x ～ sinx ～ tanx ～ arcsinx ～ arctanx ～ e ^ x - 1 ～ \ln^{x + 1} ，
\\
x - sinx ～ \frac{1}{6}x ^ 3 ， 1 - cosx ～ \frac{1}{2}x ^ 2 ， secx - 1 ～ \frac{1}{2}x ^ 2 ， tanx - x ～ \frac{1}{3}x ^ 3 ，
\\
arcsinx - x ～ \frac{1}{6}x ^ 3 ， x - arctanx ～ \frac{1}{3}x ^ 3 ，
\\
(x + 1) ^ a - 1 ～ ax(a \neq 0) ， a ^ x - 1 ～ x\ln^a ,  x - \ln^{x + 1} ～ \frac{1}{2}x ^ 2 .
$$



