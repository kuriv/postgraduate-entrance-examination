# 参数方程的导数

* [参数方程求导](#参数方程求导)
* [参数方程的二阶导数](#参数方程的二阶导数)
* [经典例题](#经典例题)

## 参数方程求导

$$
设函数 y = y(x) 由参数方程
\begin{cases}
x = \theta(t) ， \\
y = \delta(t)
\end{cases}
确定，其中 t 是参数，则 \frac{dy}{dx} = \frac{dy / dt}{dx / dt} = \frac{\theta ^ {\prime} (t)}{\delta ^ {\prime} (t)} .
$$

## 参数方程的二阶导数

$$
设函数 y = y(x) 由参数方程
\begin{cases}
x = \theta(t) ， \\
y = \delta(t)
\end{cases}
确定，其中 t 是参数，则 \frac{{d ^ 2}y}{dx ^ 2} = \frac{d(\frac{dy}{dx})}{dx} = \frac{d(\frac{dy}{dx}) / dt}{dx / dt} = \frac{\delta ^ {\prime\prime} (t) \theta ^ {\prime} (t) - \delta ^ {\prime} (t) \theta ^ {\prime\prime} (t)}{[\theta ^ {\prime} (t)] ^ 3} .
$$

## 经典例题

$$
如：计算参数方程
\begin{cases}
x = a\cos{t} ， \\
y = b\sin{t}
\end{cases}
所确定的函数 y = y(x) 的导数.
\\
\because \frac{dy}{dt} = \frac{d(b\sin{t})}{dt} = b\cos{t} ， \frac{dx}{dt} = \frac{d(a\cos{t})}{dt} = -a\sin{t} ，
\\
\therefore \frac{dy}{dx} = \frac{dy / dt}{dx / dt} = \frac{b\cos{t}}{-a\sin{t}} .
$$

$$
如：计算参数方程
\begin{cases}
x = \sin{t} ， \\
y = t\sin{t} + \cos{t}
\end{cases}
所确定的函数 y = y(x) 的二阶导数.
\\
\because \frac{dy}{dt} = \frac{d(t\sin{t} + \cos{t})}{dt} = \sin{t} + t\cos{t} - \sin{t} = t\cos{t} ， \frac{d(t\cos{t})}{dt} = \cos{t} - t\sin{t} ，
\\
\frac{dx}{dt} = \frac{d(\sin{t})}{dt} = \cos{t} ， \frac{d(\cos{t})}{dt} = -\sin{t} ，
\\
\therefore \frac{{d ^ 2}y}{dx ^ 2} = \frac{(\cos{t} - t\sin{t})\cos{t} + t\sin{t}\cos{t}}{\cos{t} ^ 3} = \frac{1}{\cos{t}} .
$$



