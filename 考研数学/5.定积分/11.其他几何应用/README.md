# 其他几何应用

* [基本公式](#基本公式)
* [经典例题](#经典例题)

## 基本公式

$$
平面上的曲边梯形的形心坐标公式： \bar{x} = \frac{\int_{a} ^ {b}{xf(x)}dx}{\int_{a} ^ {b}{f(x)}dx} ， \bar{y} = \frac{\frac{1}{2}\int_{a} ^ {b}{f ^ {2} (x)}dx}{\int_{a} ^ {b}{f(x)}dx} .
$$

$$
平面曲线的弧长公式：
\\
若平面光滑曲线由直角坐标方程 y = y(x) (a \le x \le b) 给出，则 s = \int_{a} ^ {b}{\sqrt{1 + [y ^ {\prime} (x)] ^ 2}}dx ，
\\
若平面光滑曲线由参数方程
\begin{cases}
x = x(t) ， \\
y = y(t)
\end{cases}
(\alpha \le t \le \beta) 给出，则 s = \int_{\alpha} ^ {\beta}{\sqrt{[x ^ {\prime} (t)] ^ 2 + [y ^ {\prime} (t)] ^ 2}}dt ，
\\
若平面光滑曲线由极坐标方程 r = r(\theta) (\alpha \le \theta \le \beta) 给出，则 s = \int_{\alpha} ^ {\beta}{\sqrt{[r(\theta)] ^ 2 + [r ^ {\prime} (\theta)] ^ 2}}d\theta .
$$

$$
旋转曲面的面积（侧面积）公式：\
\
\
曲线 L ： y = f(x) ， a \le x \le b ，绕 x 轴旋转一周所得旋转曲面的面积 S = 2\pi\int_{a} ^ {b}{|y|\sqrt{1 + (y_x ^ {\prime}) ^ 2}}dx ，
\\
曲线 L ：
\begin{cases}
x = x(t) ， \\
y = y(t)
\end{cases}
\alpha \le t \le \beta ， x ^ {\prime} (t) \neq 0 ，绕 x 轴旋转一周所得旋转曲面的面积 S = 2\pi\int_{\alpha} ^ {\beta}{|y(t)|\sqrt{(x_t ^ {\prime}) ^ 2 + (y_t ^ {\prime}) ^ 2}}dt ，
\\
曲线 L ： r = r(\theta) ， \alpha \le \theta \le \beta ，绕 x 轴旋转一周所得旋转曲面的面积 S = 2\pi\int_{\alpha} ^ {\beta}{|r(\theta)\sin{\theta}|\sqrt{r ^ {2} (\theta) + [r ^ {\prime} (\theta)] ^ 2}}d\theta .
$$

## 经典例题

$$
设曲线 L 的方程为 y = \frac{1}{4}x ^ 2 - \frac{1}{2}\ln{x} ， 1 \le x \le e ， D 是由曲线 L 和直线 x = 1 ， x = e 及 x 轴围成的平面图形，计算 D 的形心的横坐标.
\\
\because \bar{x} = \frac{\int_{a} ^ {b}{xf(x)}dx}{\int_{a} ^ {b}{f(x)}dx} = \frac{\int_{1} ^ {e}{x(\frac{1}{4}x ^ 2 - \frac{1}{2}\ln{x})}dx}{\int_{1} ^ {e}{(\frac{1}{4}x ^ 2 - \frac{1}{2}\ln{x})}dx} ，
\\
\int_{1} ^ {e}{x(\frac{1}{4}x ^ 2 - \frac{1}{2}\ln{x})}dx = \int_{1} ^ {e}{(\frac{1}{4}x ^ 3 - \frac{1}{2}x\ln{x})}dx = (\frac{1}{16}x ^ 4 - \frac{1}{4}x ^ 2\ln{x} + \frac{1}{8}x ^ 2)|_{1} ^ {e} = \frac{1}{16}(e ^ 2 + 1)(e ^ 2 - 3) ，
\\
\int_{1} ^ {e}{(\frac{1}{4}x ^ 2 - \frac{1}{2}\ln{x})}dx = [\frac{1}{12}x ^ 3 - \frac{1}{2}(x\ln{x} - x)]|_{1} ^ {e} = \frac{1}{12}e ^ 3 - \frac{7}{12} ，
\\
\therefore \bar{x} = \frac{3(e ^ 2 + 1)(e ^ 2 - 3)}{4(e ^ 3 - 7)} .
$$

$$
求曲线 y = \ln{(1 - x ^ 2)} 上相应于 0 \le x \le \frac{1}{2} 的一段弧的长度.
\\
\because s = \int_{a} ^ {b}{\sqrt{1 + [y ^ {\prime} (x)] ^ 2}}dx ，
\\
\therefore \int_{a} ^ {b}{\sqrt{1 + [y ^ {\prime} (x)] ^ 2}}dx = \int_{0} ^ {\frac{1}{2}}{\sqrt{1 + (-\frac{2x}{1 - x ^ 2}) ^ 2}}dx = \int_{0} ^ {\frac{1}{2}}{\frac{1 + x ^ 2}{1 - x ^ 2}}dx = \int_{0} ^ {\frac{1}{2}}{(\frac{1}{1 + x} + \frac{1}{1 - x} - 1)}dx
\\
= [\ln{(1 + x)} - \ln{(1 - x)} - x]|_{0} ^ {\frac{1}{2}} = \ln{3} - \frac{1}{2} .
$$

$$
求阿基米德螺线 r = \theta 上相应于 \theta 从 0 到 2\pi 一段的弧长.
\\
\because s = \int_{\alpha} ^ {\beta}{\sqrt{[r(\theta)] ^ 2 + [r ^ {\prime} (\theta)] ^ 2}}d\theta ，
\\
\therefore \int_{\alpha} ^ {\beta}{\sqrt{[r(\theta)] ^ 2 + [r ^ {\prime} (\theta)] ^ 2}}d\theta = \int_{0} ^ {2\pi}{\sqrt{1 + \theta ^ 2}}d\theta  = [\frac{1}{2}\theta\sqrt{1 + \theta ^ 2} + \frac{1}{2}\ln{(\theta + \sqrt{1 + \theta ^ 2})}]|_{0} ^ {2\pi} = \pi\sqrt{1 + 4\pi ^ 2} + \frac{1}{2}\ln{(2\pi + \sqrt{1 + 4\pi ^ 2})} .
$$

$$
设曲线 y = \sqrt{x - 1} (1 \le x \le 2) ，求该曲线绕 x 轴旋转一周所得到的旋转体的表面积.
\\
\because S = 2\pi\int_{a} ^ {b}{|y|\sqrt{1 + (y_x ^ {\prime}) ^ 2}}dx ，
\\
2\pi\int_{a} ^ {b}{|y|\sqrt{1 + (y_x ^ {\prime}) ^ 2}}dx = 2\pi\int_{1} ^ {2}{\sqrt{x - 1} \cdot \sqrt{1 + [(\sqrt{x - 1})\prime] ^ 2}}dx = 2\pi\int_{1} ^ {2}{\sqrt{x - 1} \cdot \frac{1}{2}\frac{\sqrt{4x - 3}}{\sqrt{x - 1}}}dx
\\
= \pi\int_{1} ^ {2}{\sqrt{4x - 3}}dx = \frac{1}{6}\pi(5\sqrt{5} - 1) .
$$

$$
设星型线的方程为
\begin{cases}
x = 2\cos ^ {3} {t} ， \\
y = 2\sin ^ {3} {t}
\end{cases}
，求绕 x 轴旋转一周而成的旋转体的表面积.
\\
\because S = 2\pi\int_{\alpha} ^ {\beta}{|y(t)|\sqrt{(x_t ^ {\prime}) ^ 2 + (y_t ^ {\prime}) ^ 2}}dt ，
\\
\therefore 2\pi\int_{\alpha} ^ {\beta}{|y(t)|\sqrt{(x_t ^ {\prime}) ^ 2 + (y_t ^ {\prime}) ^ 2}}dt = 4\pi\int_{0} ^ {\frac{\pi}{2}}{2\sin ^ {3} {t}\sqrt{[(2\cos ^ {3} {t})\prime] ^ 2 + [(2\sin ^ {3} {t})\prime] ^ 2}}dt = 4\pi\int_{0} ^ {\frac{\pi}{2}}{2\sin ^ {3} {t} \cdot 6\sin{t}\cos{t}}dt
\\
= 48\pi\int_{0} ^ {\frac{\pi}{2}}{\sin ^ {4} {t}\cos{t}}dt = 48\pi\int_{0} ^ {\frac{\pi}{2}}{\sin ^ {4} {t}}d(\sin{t}) = \frac{48}{5}\pi\sin ^ {5} {t}|_{0} ^ {\frac{\pi}{2}} = \frac{48}{5}\pi .
$$



