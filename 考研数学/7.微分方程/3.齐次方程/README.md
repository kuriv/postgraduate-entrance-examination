# 齐次方程

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)


## 定理内容

$$
如果一阶微分方程可化为 \frac{dy}{dx} = \psi(\frac{y}{x}) 的形式，那么就称该方程为齐次方程.
\\
在齐次方程 \frac{dy}{dx} = \psi(\frac{y}{x}) 中，引入新的未知函数 u = \frac{y}{x} ，就可将其化为可分离变量的微分方程.
\\
因为 y = ux ， \frac{dy}{dx} = x\frac{du}{dx} + u ，则 \psi(u) = x\frac{du}{dx} + u ， x\frac{du}{dx} = \psi(u) - u ，
\\
分离变量后得， \frac{du}{\psi(u) - u} = \frac{dx}{x} ，再对两边同时积分，最后将 \frac{y}{x} 代入 u ，即可得到该齐次方程的通解.
$$

$$
方程 \frac{dy}{dx} = \frac{ax + by + c}{a_1x + b_1x + c_1} 当 c = c_1 = 0 是齐次的，否则不是齐次的.
\\
可以令 x = X + h ， y = Y + h ， dx = dX ， dy = dY ，则原方程为 \frac{dY}{dX} = \frac{aX + bY + ah + bk + c}{a_1X + b_1Y + a_1h + b_1k + c_1} ，
\\
如果方程组
\begin{cases}
ah + bk + c = 0 \\
a_1h + b_1k + c_1 = 0 ，
\end{cases}
\\
则原方程便可化为齐次方程，分离变量并积分后，将 x - h 代入 X ， y - k 代入 Y ，即可求得该齐次方程的通解.
$$

## 经典例题

### 例题一

$$
如：解方程 y ^ 2 + x ^ 2\frac{dy}{dx} = xy\frac{dy}{dx} .
\\
\because \frac{dy}{dx} = \frac{y ^ 2}{xy - x ^ 2} = \frac{(\frac{y}{x}) ^ 2}{\frac{y}{x} - 1} ，
\\
令 u = \frac{y}{x} ， \frac{dy}{dx} = x\frac{du}{dx} + u ，
\\
\therefore x\frac{du}{dx} + u = \frac{u ^ 2}{u - 1} ， x\frac{du}{dx} = \frac{u}{u - 1} ，
\\
\therefore \frac{dx}{x} = \frac{u - 1}{u}du ， \int{\frac{1}{x}}dx = \int{\frac{u - 1}{u}}du ，
\\
\therefore \ln ^ {|x|} = u - \ln ^ {|u|} + C ，即 \ln ^ {|ux|} = u + C ，
\\
将 \frac{y}{x} 代入 u ，则该方程的通解为 \ln ^ {|y|} = \frac{y}{x} + C .
$$

### 例题二

$$
如：解方程 (2x + y -4)dx + (x + y - 1)dy = 0 .
\\
令 x = X + h ， y = Y + k ，则 dx = dX ， dy = dY ，
\\
代入原方程， (2X + Y + 2h + k - 4)dX + (X + Y + h + k - 1)dY = 0 ，
\\
解方程组
\begin{cases}
2h + k - 4 = 0 \\
h + k - 1 = 0 ，
\end{cases}
\\
\therefore h = 3 ， k = -2 ，
\\
再令 x = X + 3 ， y = Y - 2 ，
\\
再代入原方程， (2X + Y)dX + (X + Y)dY = 0 ，
\\
\therefore \frac{dY}{dX} = -\frac{2X + Y}{X + Y} = -\frac{2 + \frac{Y}{X}}{1 + \frac{Y}{X}} ，
\\
令 u = \frac{Y}{X} ， \frac{dY}{dX} = X\frac{du}{dX} + u ，
\\
\therefore -\frac{2 + u}{1 + u} = X\frac{du}{dX} + u ， X\frac{du}{dX} = -\frac{u ^ 2 + 2u + 2}{1 + u} ，
\\
\therefore \frac{dX}{X} = -\frac{1 + u}{u ^ 2 + 2u + 2}du ， \int{\frac{1}{X}}dX = -\int{\frac{1 + u}{u ^ 2 + 2u + 2}}du ，
\\
\therefore \ln ^ {|X|} = -\frac{1}{2}\ln ^ {|u ^ 2 + 2u + 2|} + \ln ^ C ，即 X ^ 2(u ^ 2 + 2u + 2) = C ，
\\
\therefore Y ^ 2 + 2XY + 2X ^ 2 = C ，
\\
将 X = x - 3 ， Y = y + 2 分别代入，则该方程的通解为 2x ^ 2 + y ^ 2 + 2xy - 8x - 2y = C .
$$



