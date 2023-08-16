# 隐函数的导数

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

$$
如：求由方程 x - y + \frac{1}{2}siny = 0 所确定的隐函数的二阶导数 \frac{{d ^ 2}y}{dx ^ 2} .
\\
先对方程左边对 x 求导数，即 \frac{d}{dx}(x - y + \frac{1}{2}siny) = {1 - \frac{dy}{dx} + \frac{1}{2}cosy \cdot \frac{dy}{dx}} ，
\\
再对方程右边对 x 求导数，即 (0)\prime = 0 ，
\\
\therefore {1 - \frac{dy}{dx} + \frac{1}{2}cosy \cdot \frac{dy}{dx}} = 0 ，
\\
\therefore \frac{dy}{dx} = \frac{1}{1 - \frac{1}{2}cosy} = \frac{2}{2 - cosy} .
\\
再对 \frac{dy}{dx} 求导，即 \frac{2}{2 - cosy} = \frac{-2siny \cdot \frac{dy}{dx}}{(2 - cosy) ^ 2} ，
\\
将 \frac{dy}{dx} 代入，即 \frac{{d ^ 2}y}{dx ^ 2} = \frac{-2siny \cdot \frac{2}{2 - cosy}}{(2 - cosy) ^ 2} = \frac{-4siny}{(1 - cosy) ^ 3} .
$$

$$
注：在某些场合，利用对数求导法求导数比用通常的方法简便.
\\
如：求 y = x ^ {sinx} (x > 0) 的导数.
\\
先对方程两边取对数，即 \ln ^ y = \ln ^ {x ^ {sinx}} = sinx \cdot \ln ^ x ，
\\
然后对方程左边对 x 求导数，即 \frac{d}{dx}(\ln ^ y) = \frac{1}{y} \cdot \frac{dy}{dx} ，
\\
再对方程右边对 x 求导数，即 \frac{d}{dx}(sinx \cdot \ln ^ x) = cosx \cdot \ln^x + sinx \cdot \frac{1}{x} ，
\\
\therefore \frac{1}{y} \cdot \frac{dy}{dx} = cosx \cdot \ln^x + sinx \cdot \frac{1}{x} ，
\\
\therefore \frac{dy}{dx} = y \cdot (cosx \cdot \ln^x + sinx \cdot \frac{1}{x}) = x ^ {sinx} \cdot (cosx \cdot \ln^x + sinx \cdot \frac{1}{x}) .
$$



