# 定积分的计算

* [定理内容](#定理内容)
* [换元积分法](#换元积分法)
* [分部积分法](#分部积分法)
* [重要结论](#重要结论)
* [经典例题](#经典例题)

## 定理内容

$$
若 f(x) 在 [a , b] 上有原函数 F(x) ，则 \int_a ^ {b}{f(x)}dx = F(b) - F(a) .
$$

$$
若 f(x) 在 [a , b] 上分段有原函数，则 \int_a ^ {b}{f(x)}dx = \int_a ^ {c}{f(x)}dx + \int_c ^ {b}{f(x)}dx = F_1(c_{-0}) - F_1(a) + F_2(b) - F_2(c_{+0}) .
$$

## 换元积分法

$$
设 f(x) 在 [a , b] 上连续，函数 x = \phi(t) 满足 \phi(\alpha) = a ， \phi(\beta) = b ， 且在 [\alpha , \beta] 上有连续的导数，值域为 R_{\phi} = [a , b] ，
\\
\int_a ^ {b}{f(x)}dx = \int_\alpha ^ {\beta}{f[\phi(t)]\phi(t)\prime}dt .
$$

## 分部积分法

$$
\int_a ^ {b}{u(x)v(x)\prime}dx = u(x)v(x)\prime|_a ^ {b} - \int_a ^ {b}{v(x)u(x)\prime}dx .
$$

## 重要结论

$$
设 f(x) 为连续的偶函数，则 \int_{-a} ^ {a}{f(x)}dx = 2\int_0 ^ {a}{f(x)}dx .
\\
设 f(x) 为连续的奇函数，则 \int_{-a} ^ {a}{f(x)}dx = 0 .
$$

$$
设 f(x) 是以 T 为周期的连续函数，则对任意的实数 a ，都有 \int_a ^ {a + T}{f(x)}dx = \int_0 ^ {T}{f(x)}dx .
\\
即在长度为一个周期的区间上的定积分，与该区间的起点位置无关.
$$

$$
设 f(x) 为连续函数，则 \int_a ^ {b}{f(x)}dx = \int_a ^ {b}{f(a + b - x)}dx （区间再现公式）.
$$

$$
华里士公式：
\\
\int_0 ^ {\frac{\pi}{2}}{\sin ^ n {x}}dx = \int_0 ^ {\frac{\pi}{2}}{\cos ^ n {x}}dx =
\begin{cases}
\frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{2}{3} \cdot 1 ， n 为大于 1 的奇数， \\
\frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{1}{2} \cdot \frac{\pi}{2} ， n 为大于 1 的偶数.
\end{cases}
\\
\int_0 ^ {\pi}{\sin ^ n {x}}dx =
\begin{cases}
2 \cdot \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{2}{3} \cdot 1 ， n 为大于 1 的奇数， \\
2 \cdot \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{1}{2} \cdot \frac{\pi}{2} ， n 为大于 1 的偶数.
\end{cases}
\\
\int_0 ^ {\pi}{\cos ^ n {x}}dx =
\begin{cases}
0 ， n 为正奇数， \\
2 \cdot \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{1}{2} \cdot \frac{\pi}{2} ， n 为正偶数.
\end{cases}
\\
\int_0 ^ {2\pi}{\sin ^ n {x}}dx = \int_0 ^ {2\pi}{\cos ^ n {x}}dx
\begin{cases}
0 ， n 为正奇数， \\
4 \cdot \frac{n - 1}{n} \cdot \frac{n - 3}{n - 2} \cdot \cdots \cdot \frac{1}{2} \cdot \frac{\pi}{2} ，  n 为正偶数.
\end{cases}
\\
利用华里士公式可以快速计算某些特殊的定积分，如：
\\
\int_0 ^ {\frac{\pi}{2}}{\sin ^ {8} {x}}dx = \frac{7}{8} \cdot \frac{5}{6} \cdot \frac{3}{4} \cdot \frac{1}{2} \cdot \frac{\pi}{2} = \frac{35}{256}\pi ，
\\
\int_0 ^ {\pi}{\sin ^ {9} {x}}dx = 2 \cdot \frac{8}{9} \cdot \frac{6}{7} \cdot \frac{4}{5} \cdot \frac{2}{3} \cdot 1 = \frac{256}{315} .
$$

## 经典例题

$$
如：设 f(x + \frac{1}{x}) = \frac{x + x ^ 3}{1 + x ^ 4} ，求 \int_2 ^ {2\sqrt{2}}{f(x)}dx .
\\
\because f(x + \frac{1}{x}) = \frac{x + x ^ 3}{1 + x ^ 4} = \frac{x + \frac{1}{x}}{x ^ 2 + \frac{1}{x ^ 2}} = \frac{x + \frac{1}{x}}{(x + \frac{1}{x}) ^ 2 -2} ，
\\
\therefore f(x) = \frac{x}{x ^ 2 -2} ，
\\
\therefore \int_2 ^ {2\sqrt{2}}{f(x)}dx = \int_2 ^ {2\sqrt{2}}{\frac{x}{x ^ 2 -2}}dx = \frac{1}{2}\int_2 ^ {2\sqrt{2}}{\frac{1}{x ^ 2 -2}}d(x ^ 2 - 2) = \frac{1}{2}\ln{(x ^ 2 - 2)}|_2 ^ {2\sqrt{2}} = \frac{1}{2}(\ln{6} - \ln{2}) = \frac{1}{2}\ln{3} .
$$

$$
如：求 \int_{-1} ^ {1}{x ^ 2 \sqrt{1 - x ^ 2}}dx .
\\
\because {x ^ 2 \sqrt{1 - x ^ 2}} 是偶函数，则 \int_{-1} ^ {1}{x ^ 2 \sqrt{1 - x ^ 2}}dx = 2\int_0 ^ {1}{x ^ 2 \sqrt{1 - x ^ 2}}dx ，
\\
令 x = \sin{t} ，则 x ^ 2 \sqrt{1 - x ^ 2} = \sin ^ {2} {t} \sqrt{1 - \sin ^ {2} {t}} = \sin ^ {2} {t} \cos{t} ， d(x) = \cos{t}dt ，
\\
当 x = 0 时，可取 t = 0 ，当 x = 1 时，可取 t = \frac{\pi}{2} ，
\\
\therefore 2\int_0 ^ {1}{x ^ 2 \sqrt{1 - x ^ 2}}dx = 2\int_0 ^ {\frac{\pi}{2}}{\sin ^ {2} {t} \cos ^ {2} {t}}dx = 2\int_0 ^ {\frac{\pi}{2}}{\sin ^ {2} {t}(1 - \sin ^ {2} {t})}dx = 2\int_0 ^ {\frac{\pi}{2}}{\sin ^ {2} {t} - \sin ^ {4} {t}}dx = 2(\frac{1}{2} \cdot \frac{\pi}{2}- \frac{3}{4} \cdot \frac{1}{2} \cdot \frac{\pi}{2}) = \frac{\pi}{8} .
$$

$$
如：求 \int_0 ^ {1}{\arcsin{\sqrt{1 - x ^ 2}}}dx .
\\
令 x = \cos{t} ，则 \arcsin{\sqrt{1 - x ^ 2}} = \arcsin{\sqrt{1 - \cos ^ {2} {t}}} = \arcsin({\sin{t}}) ， d(x) = -\sin{t}dt ，
\\
当 x = 0 时，可取 t = \frac{\pi}{2} ，当 x = 1 时，可取 t = 0 ，
\\
\therefore \int_{0} ^ {1}{\arcsin{\sqrt{1 - x ^ 2}}}dx = \int_{\frac{\pi}{2}} ^ {0}{\arcsin(\sin{t}) \cdot (-\sin{t})}dt = \int_{0} ^ {\frac{\pi}{2}}{t\sin{t}}dt
\\
= \int_{0} ^ {\frac{\pi}{2}}{t}d(-\cos{t}) = -t\cos{t}|_{0} ^ {\frac{\pi}{2}} + \int_{0} ^ {\frac{\pi}{2}}{\cos{t}}dt = \sin{t}|_{0} ^ {\frac{\pi}{2}} = 1 .
$$

$$
如：求 \int_{0} ^ {1}{x\arcsin{\sqrt{4x - 4x ^ 2}}}dx .
\\
\because 4x - 4x ^ 2 = 1 - (1 - 2x) ^ 2 ，
\\
令 1 - 2x = t ，则 x = \frac{1 - t}{2} ， x\arcsin{\sqrt{4x - 4x ^ 2}} = \frac{1 - t}{2}\arcsin{\sqrt{1 - t ^ 2}} ， d(x) = -\frac{1}{2}dt ，
\\
当 x = 0 时，可取 t = 1 ，当 x = 1 时，可取 t = -1 ，
\\
\therefore \int_{0} ^ {1}{x\arcsin{\sqrt{4x - 4x ^ 2}}}dx = \int_{1} ^ {-1}{\frac{1 - t}{2}}\arcsin{\sqrt{1 - t ^ 2}} \cdot -\frac{1}{2}dt = \frac{1}{4}\int_{-1} ^ {1}(1 - t)\arcsin{\sqrt{1 - t ^ 2}}dt
\\
= \frac{1}{4}\int_{-1} ^ {1}\arcsin{\sqrt{1 - t ^ 2}}dt - \frac{1}{4}\int_{-1} ^ {1}t\arcsin{\sqrt{1 - t ^ 2}}dt ，
\\
= \frac{1}{2}\int_{0} ^ {1}{\sqrt{1 - t ^ 2}}dt = \frac{1}{2} .
$$

$$
如：设 f(x) 在 [0 , 1] 上连续，证明 \int_{0} ^ {\pi}{xf(\sin{x})}dx = \frac{\pi}{2}\int_{0} ^ {\pi}{f(\sin{x})}dx ，并计算 \int_{0} ^ {\pi}{x\sin ^ {9} {x}}dx .
\\
令 x = \pi - t ，则 d(x) = -dt ， \int_{0} ^ {\pi}{xf(\sin{x})}dx = \int_{0} ^ {\pi}{(\pi - t)f[\sin{(\pi - t)}]}dt = \int_{0} ^ {\pi}{(\pi - t)f(\sin{t})}dt
\\
= \pi\int_{0} ^ {\pi}{f(\sin{t})}dt - \int_{0} ^ {\pi}{tf(\sin{t})}dt = \pi\int_{0} ^ {\pi}{f(\sin{x})}dx - \int_{0} ^ {\pi}{xf(\sin{x})}dx ，
\\
\therefore \int_{0} ^ {\pi}{xf(\sin{x})}dx = \frac{\pi}{2}\int_{0} ^ {\pi}{f(\sin{x})}dx ，
\\
\therefore \int_{0} ^ {\pi}{x\sin ^ {9} {x}}dx = \frac{\pi}{2}\int_{0} ^ {\pi}{\sin ^ {9} {x}}dx = \frac{\pi}{2} \cdot 2 \cdot \frac{8}{9} \cdot \frac{6}{7} \cdot \frac{4}{5} \cdot \frac{2}{3} \cdot 1 = \frac{128}{315}\pi .
$$



