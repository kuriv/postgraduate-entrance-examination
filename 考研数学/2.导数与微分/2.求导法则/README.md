# 求导法则

* [有理运算法则](#有理运算法则)
* [复合函数求导](#复合函数求导)
* [反函数求导](#反函数求导)

## 有理运算法则

$$
(u \pm v)\prime = u\prime \pm v\prime
\\
(Cu)\prime = Cu\prime
\\
(uv)\prime = {u\prime}v + u{v\prime}
\\
(\frac{u}{v})\prime = \frac{{u\prime}v - u{v\prime}}{v ^ 2}
$$

## 复合函数求导

$$
设 u = g(x) 在 x 处可导， y = f(u) 在对应点处可导，则复合函数 f[g(x)] 在 x 处可导，且 \frac{dy}{dx} = \frac{dy}{du} \ast \frac{du}{dx} = {f(u)}\prime{g(x)}\prime
\\
如： (\ln{cos(x - 1)})\prime = \frac{1}{cos(x - 1)} \ast -sin(x - 1) \ast 1 = \frac{-sin(x - 1)}{cos(x - 1)} = -tan(x - 1)
$$

## 反函数求导

$$
简单的说，反函数的导数等于直接函数导数的导数，即 \frac{dy}{dx} = \frac{1}{\frac{dx}{dy}}
\\
如： (arcsinx)\prime = \frac{1}{(sinx)\prime} ， (arccosx)\prime = \frac{1}{(cosx)\prime} ，
\\
(arctanx)\prime = \frac{1}{(tanx)\prime} ， (arccotx)\prime = \frac{1}{(cotx)\prime} ， 
\\
(log_a^{x})\prime = \frac{1}{(a ^ y)\prime} .
$$



