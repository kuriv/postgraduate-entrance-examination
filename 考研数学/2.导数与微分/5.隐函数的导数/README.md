# 隐函数的导数

* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)

## 经典例题

### 例题一

$$
如：求由方程 e ^ y + xy - e = 0 所确定的隐函数的导数 \frac{dy}{dx} .
\\
先对方程左边对 x 求导数，即 \frac{d}{dx}(e ^ y + xy - e) = e ^ y \cdot \frac{dy}{dx} + y + x \cdot \frac{dy}{dx} ，
\\
再对方程右边对 x 求导数，即 (0)\prime = 0 ，
\\
\therefore e ^ y \cdot \frac{dy}{dx} + y + x \cdot \frac{dy}{dx} = 0 ，
\\
\therefore \frac{dy}{dx} = -\frac{y}{e ^ y + x} .
$$

### 例题二

$$
如：求由方程 x - y + \frac{1}{2}\sin{y} = 0 所确定的隐函数的二阶导数 \frac{{d ^ 2}y}{dx ^ 2} .
\\
先对方程左边对 x 求导数，即 \frac{d}{dx}(x - y + \frac{1}{2}\sin{y}) = {1 - \frac{dy}{dx} + \frac{1}{2}\cos{y} \cdot \frac{dy}{dx}} ，
\\
再对方程右边对 x 求导数，即 (0)\prime = 0 ，
\\
\therefore {1 - \frac{dy}{dx} + \frac{1}{2}\cos{y} \cdot \frac{dy}{dx}} = 0 ，
\\
\therefore \frac{dy}{dx} = \frac{1}{1 - \frac{1}{2}\cos{y}} = \frac{2}{2 - \cos{y}} ，
\\
再对 \frac{dy}{dx} 求导，即 \frac{d}{dx}(\frac{2}{2 - \cos{y}}) = \frac{-2\sin{y} \cdot \frac{dy}{dx}}{(2 - \cos{y}) ^ 2} ，
\\
将 \frac{dy}{dx} 代入，即 \frac{{d ^ 2}y}{dx ^ 2} = \frac{-2\sin{y} \cdot \frac{2}{2 - \cos{y}}}{(2 - \cos{y}) ^ 2} = \frac{-4\sin{y}}{(1 - \cos{y}) ^ 3} .
$$

### 例题三

$$
注：在某些场合，利用对数求导法求导数比用通常的方法简便.
\\
如：求 y = x ^ {\sin{x}} (x > 0) 的导数.
\\
先对方程两边取对数，即 \ln ^ y = \ln ^ {x ^ {\sin{x}}} = \sin{x} \cdot \ln ^ x ，
\\
然后对方程左边对 x 求导数，即 \frac{d}{dx}(\ln ^ y) = \frac{1}{y} \cdot \frac{dy}{dx} ，
\\
再对方程右边对 x 求导数，即 \frac{d}{dx}(\sin{x} \cdot \ln ^ x) = \cos{x} \cdot \ln ^ x + \sin{x} \cdot \frac{1}{x} ，
\\
\therefore \frac{1}{y} \cdot \frac{dy}{dx} = \cos{x} \cdot \ln ^ x + \sin{x} \cdot \frac{1}{x} ，
\\
\therefore \frac{dy}{dx} = y \cdot (\cos{x} \cdot \ln ^ x + \sin{x} \cdot \frac{1}{x}) = x ^ {\sin{x}} \cdot (\cos{x} \cdot \ln ^ x + \sin{x} \cdot \frac{1}{x}) .
$$



