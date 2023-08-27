# 参数方程的导数

* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)

## 经典例题

### 例题一

$$
如：计算参数方程
\begin{cases}
x = a\cos{t} ， \\
y = b\sin{t}
\end{cases}
所确定的函数 y = y(x) 的导数.
\\
\because \frac{dy}{dt} = \frac{d}{dt}(b\sin{t}) = b\cos{t} ， \frac{dx}{dt} = \frac{d}{dt}(a\cos{t}) = -a\sin{t} ，
\\
\therefore \frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{b\cos{t}}{-a\sin{t}} .
$$

### 例题二

$$
如：计算参数方程
\begin{cases}
x = a(t - \sin{t}) ， \\
y = a(1 - \cos{t})
\end{cases}
所确定的函数 y = y(x) 的二阶导数.
\\
\because \frac{dy}{dt} = \frac{d}{dt}(a(1 - \cos{t})) = a\sin{t} ， \frac{dx}{dt} = \frac{d}{dt}(a(t - \sin{t})) = a(1 - \cos{t}) ，
\\
\therefore \frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{a\sin{t}}{a(1 - \cos{t})} = \frac{\sin{t}}{1 - \cos{t}} = \cot\frac{t}{2} ，
\\
\therefore \frac{{d ^ 2}y}{dx ^ 2} = \frac{\frac{dy}{dx}}{dx} = \frac{\frac{\frac{dy}{dx}}{dt}}{\frac{dx}{dt}} = \frac{-\frac{1}{2}(\csc\frac{t}{2}) ^ 2}{a(1 - \cos{t})} .
$$



