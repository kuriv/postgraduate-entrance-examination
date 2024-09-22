# 旋转体体积

* [基本公式](#基本公式)
* [经典例题](#经典例题)

## 基本公式

$$
曲线 y = y(x) 与 x = a ， x = b (a \lt b) 及 x 轴围成的曲边梯形，绕 x 轴旋转一周所得到的旋转体体积 V_x = \int_{a} ^ {b}{\pi{y ^ {2} (x)}}dx .
$$

$$
曲线 y = y(x) 与 x = a ， x = b (0 \le a \lt b) 及 x 轴围成的曲边梯形，绕 y 轴旋转一周所得到的旋转体体积 V_y = 2\pi\int_{a} ^ {b}{x|y(x)|}dx .
$$

$$
设平面曲线 y = f(x) ， a \le x \le b ，绕直线 Ax + By + C = 0 旋转一周所得到的旋转体体积 V = \frac{\pi}{(A ^ 2 + B ^ 2) ^ {\frac{3}{2}}}\int_{a} ^ {b}{[Ax + Bf(x) + C] ^ 2|Af ^ {\prime} (x) - B|}dx .
$$

## 经典例题

$$
求曲线 y = e ^ {-\frac{x}{2}}\sqrt{\sin{x}} 在 [0 , 2\pi] 部分与 x 轴围成的平面图形绕 x 轴旋转一周所成的旋转体的体积.
\\
\because y = e ^ {-\frac{x}{2}}\sqrt{\sin{x}} 在 [0 , \pi] 上存在，在 [\pi , 2\pi] 上不存在，
\\
\therefore V_x = \int_{a} ^ {b}{\pi{y ^ {2} (x)}}dx = \int_{0} ^ {\pi}{\pi(e ^ {-\frac{x}{2}}\sqrt{\sin{x}}) ^ 2}dx = \pi\int_{0} ^ {\pi}{e ^ {-x}\sin{x}}dx
\\
=
\frac{\pi}{2}\left|
\begin{array}{} 
(e ^ {-x})\prime & \sin ^ {\prime} {x} \\ 
e ^ {-x}         & \sin{x} \\ 
\end{array}
\right|_{0} ^ {\pi}
= \frac{\pi}{2}(-e ^ {-x} \cdot \sin{x} - \cos{x} \cdot e ^ {-x})|_{0} ^ {\pi} = -\frac{\pi}{2}e ^ {-x}(\sin{x} + \cos{x})|_{0} ^ {\pi} = \frac{\pi}{2}(\ e ^ {-x} + 1) .
$$

$$
设函数 f(x) 的定义域为 (0 , +\infty) ，且满足 2f(x) + x ^ 2{f(\frac{1}{x})} = \frac{x ^ 2 + 2x}{\sqrt{1 + x ^ 2}} ，求曲线 y = f(x) ， y = \frac{1}{2} ， y = \frac{\sqrt{3}}{2} 及 y 轴所围图形绕 x 轴所成旋转体的体积.
\\
\because 2f(x) + x ^ 2{f(\frac{1}{x})} = \frac{x ^ 2 + 2x}{\sqrt{1 + x ^ 2}} ，则 2f(\frac{1}{x}) + \frac{1}{x ^ 2}f(x) = \frac{\frac{1}{x ^ 2} + \frac{2}{x}}{\sqrt{1 + \frac{1}{x ^ 2}}} ， 2{x ^ 2}f(\frac{1}{x}) + f(x) = \frac{1 + 2x}{\sqrt{1 + \frac{1}{x ^ 2}}} = \frac{x + 2{x ^ 2}}{\sqrt{x ^ 2 + 1}} ，
\\
\therefore f(x) = y = \frac{x}{\sqrt{1 + x ^ 2}} ，
\\
\therefore x = \frac{y}{\sqrt{1 - y ^ 2}} ，
\\
\therefore V = 2\pi\int_{a} ^ {b}{x|y(x)|}dx = 2\pi\int_{a} ^ {b}{xy}dy = 2\pi\int_{\frac{1}{2}} ^ {\frac{\sqrt{3}}{2}}{\frac{y ^ 2}{\sqrt{1 - y ^ 2}}}dy ，
\\
令 y = \sin{t} ，则 \frac{y ^ 2}{\sqrt{1 - y ^ 2}} = \frac{\sin ^ {2} {t}}{\sqrt{1 - \sin ^ {2} {t}}} = \frac{\sin ^ {2} {t}}{\cos{t}} ， d(y) = \cos{t}dt ，
\\
当 y = \frac{1}{2} 时，可取 t = \frac{\pi}{6} ，当 y = \frac{\sqrt{3}}{2} 时，可取 t = \frac{\pi}{3} ，
\\
\therefore 2\pi\int_{\frac{1}{2}} ^ {\frac{\sqrt{3}}{2}}{\frac{y ^ 2}{\sqrt{1 - y ^ 2}}}dy = 2\pi\int_{\frac{\pi}{6}} ^ {\frac{\pi}{3}}{\frac{\sin ^ {2} {t}}{\cos{t}} \cdot \cos{t}}dt = 2\pi\int_{\frac{\pi}{6}} ^ {\frac{\pi}{3}}{\sin ^ {2} {t}}dt = \frac{1}{2} \cdot 2\pi\int_{\frac{\pi}{6}} ^ {\frac{\pi}{3}}{(1 - \cos{2t})}dt = \frac{\pi ^ 2}{6} .
$$

$$
过坐标原点作曲线 y = e ^ x 的切线，该切线与曲线 y = e ^ x 以及 x 轴围成的向 x 轴负向无限伸展的平面图形记为 D ，求 D 的面积，
\\
并求 D 绕直线 x = 1 旋转一周所成的旋转体的体积 V .
\\
\because 易知 y = e ^ x 的切线为 y = ex ，且交点为 (1 , e) ，
\\
\therefore y = e ^ x \Rightarrow x = \ln{y} ， y = ex \Rightarrow x = \frac{y}{e} ，
\\
\therefore D = \int_{0} ^ {e}{(\frac{y}{e} - \ln{y})}dy = (\frac{y ^ 2}{2e} - y\ln{y} + y)|_{0} ^ {e} = \frac{e}{2} ，
\\
\therefore V = V_大 - V_小 = \int_{a} ^ {b}{\pi{y_{大} ^ {2} (x)}}dx - \int_{a} ^ {b}{\pi{y_{小} ^ {2} (x)}}dx = \pi\int_{0} ^ {e}{[(1 - \ln{y}) ^ 2 - (1 - \frac{y}{e}) ^ 2]}dy = \pi\int_{0} ^ {e}{(\ln ^ {2} {y} - 2\ln{y} + \frac{2y}{e} - \frac{y ^ 2}{e ^ 2})}dy
\\
= \pi(y\ln ^ {2} {y} - 4y\ln{y} + 4y +\frac{y ^ 2}{e} - \frac{y ^ 3}{3e ^ 2})|_{0} ^ {e} = \frac{5}{3}\pi{e} .
$$

$$
求曲线 y = \sqrt{x} 与 y = x 所围平面有界区域绕直线 y = x 旋转一周所得旋转体的体积.
\\
\because 易知 y = \sqrt{x} 与 y = x 的交点为 (1 , 1) ，
\\
\because y = x \Rightarrow x - y = 0 \Rightarrow A = 1 ， B = -1 ， C = 0 ，
\\
\therefore V = \frac{\pi}{(A ^ 2 + B ^ 2) ^ {\frac{3}{2}}}\int_{a} ^ {b}{[Ax + Bf(x) + C] ^ 2|Af ^ {\prime} (x) - B|}dx = \frac{\pi}{2\sqrt{2}}\int_{0} ^ {1}{(x - \sqrt{x}) ^ 2(\frac{1}{2\sqrt{x}} + 1)}dx
\\
= \frac{\pi}{2\sqrt{2}}\int_{0} ^ {1}{(x ^ 2 - \frac{3}{2}x ^ {\frac{3}{2}} + \frac{1}{2}x ^ {\frac{1}{2}})}dx = \frac{\pi}{2\sqrt{2}}(\frac{1}{3}x ^ 3 - \frac{3}{5}x ^ {\frac{5}{2}} + \frac{1}{3}x ^ {\frac{3}{2}})|_{0} ^ {1} = \frac{\sqrt{2}}{60}\pi .
$$



