# 平面图形面积

* [基本公式](#基本公式)
* [经典例题](#经典例题)

## 基本公式

$$
曲线 y = y_1(x) 与 y = y_2(x) 及 x = a ， x = b (a \lt b) 所围成平面图形的面积： S = \int_{a} ^ {b}{|y_1(x) - y_2(x)|}dx .
$$

$$
曲线 r = r_1(\theta) 与 r = r_2(\theta) 及两射线 \theta = \alpha ， \theta = \beta (0 \lt \beta - \alpha \lt 2\pi) 所围成的曲边扇形的面积： S = \frac{1}{2}\int_{\alpha} ^ {\beta}{|r_1 ^ {2} (\theta) - r_2 ^ {2} (\theta)|}d\theta .
$$

$$
参数方程下的问题是重点，
\begin{cases}
x = x(t) ， \\
y = y(t) 
\end{cases}
\Rightarrow S = \int_{0} ^ {2\pi{a}}{f(x)}dx = \int_{0} ^ {2\pi}{y(t)}d[x(t)] .
$$

## 经典例题

$$
设 A_n 是曲线 y = x ^ n 与 y = x ^ {n + 1} (n = 1 , 2 , \cdots) 所围区域的面积，计算 \lim_{n \to \infty} (2\sum_{k = 1} ^ {n} A_k) ^ n .
\\
\because y = x ^ n 与 y = x ^ {n + 1} 的交点为 (0 , 0) 与 (1 , 1) ，
\\
\therefore A_n = \int_{a} ^ {b}{|y_1(x) - y_2(x)|}dx = \int_{0} ^ {1}{(x ^ n - x ^ {n + 1})}dx = \frac{1}{n + 1}x ^ {n + 1}|_{0} ^ {1} - \frac{1}{n + 2}x ^ {n + 2}|_{0} ^ {1} = \frac{1}{n + 1} - \frac{1}{n + 2} ，
\\
\therefore \lim_{n \to \infty} (2\sum_{k = 1} ^ {n} A_k) ^ n = \lim_{n \to \infty} [\sum_{k = 1} ^ {n} (\frac{2}{k + 1} - \frac{2}{k + 2})] ^ n = \lim_{n \to \infty} (\frac{2}{2} - \frac{2}{3} + \frac{2}{3} - \frac{2}{4} + \cdots + \frac{2}{n + 1} - \frac{2}{n + 2}) ^ n = \lim_{n \to \infty} (1 - \frac{2}{n + 2}) ^ n
\\
= \lim_{n \to \infty} e ^ {n \cdot -\frac{2}{n + 2}} = \lim_{n \to \infty} e ^ {-\frac{2n}{n + 2}} = e ^ {-2} .
$$

$$
求伯努利双纽线 r ^ 2 = a ^ 2\cos{2\theta} 围成的图形面积.
\\
由伯努利双纽线图形对称性可得， S = \frac{1}{2}\int_{\alpha} ^ {\beta}{|r_1 ^ {2} (\theta) - r_2 ^ {2} (\theta)|}d\theta = 4 \cdot \frac{1}{2}\int_{0} ^ {\frac{\pi}{4}}{a ^ 2\cos{2\theta}}d\theta = 2a ^ 2\int_{0} ^ {\frac{\pi}{4}}{\cos{2\theta}}d\theta = a ^ 2 .
$$

$$
求由摆线
\begin{cases}
x = a(t - \sin{t}) ， \\
y = a(1 - \cos{t}) 
\end{cases}
(a \gt 0) 的一拱与 x 轴所围平面图形的面积.
\\
\because 当 t = 0 或 t = 2\pi 时， y = 0 ，则此时曲线正好变成一拱，
\\
\therefore S = \int_{0} ^ {2\pi{a}}{f(x)}dx = \int_{0} ^ {2\pi}{a(1 - \cos{t})}d[a(t - \sin{t})] = \int_{0} ^ {2\pi}{a ^ 2(1 - \cos{t}) ^ 2}dt = a ^ 2\int_{0} ^ {2\pi}{(1 - 2\cos{t} + \cos ^ {2} {t})}dt
\\
= a ^ 2(\int_{0} ^ {2\pi}{1}dt - \int_{0} ^ {2\pi}{2\cos{t}}dt + \int_{0} ^ {2\pi}{\cos ^ {2} {t}}dt) = a ^ 2(2\pi - 0 + \pi) = 3{a ^ 2}\pi .
$$



