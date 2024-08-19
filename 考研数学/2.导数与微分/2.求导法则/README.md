# 求导法则

* [有理运算法则](#有理运算法则)
* [复合函数求导](#复合函数求导)
* [反函数求导](#反函数求导)
* [经典例题](#经典例题)


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
设 u = g(x) 在 x 处可导， y = f(u) 在对应点处可导，则复合函数 f[g(x)] 在 x 处可导，且 \frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = {f(u)}\prime{g(x)}\prime .
$$

## 反函数求导

$$
反函数的导数等于其直接函数导数的倒数，即 \frac{dy}{dx} = \frac{1}{\frac{dx}{dy}} .
\\
(\arcsin{x})\prime = \frac{1}{(\sin{y})\prime}
\\
(\arccos{x})\prime = \frac{1}{(\cos{y})\prime}
\\
(\arctan{x})\prime = \frac{1}{(\tan{y})\prime}
\\
(arccotx)\prime = \frac{1}{(\cot{y})\prime}
\\
(\log_a^{x})\prime = \frac{1}{(a ^ y)\prime}
$$

## 经典例题

$$
如：求 \ln[\cos{(x - 1)}] 的导数.
\\
\because \ln[\cos{(x - 1)}]\prime = \frac{1}{\cos{(x - 1)}} \cdot -\sin{(x - 1)} \cdot 1 = \frac{-\sin{(x - 1)}}{\cos{(x - 1)}} = -\tan{(x - 1)} .
\\
\therefore \ln[\cos{(x - 1)}] 的导数为 -\tan{(x - 1)} .
$$



