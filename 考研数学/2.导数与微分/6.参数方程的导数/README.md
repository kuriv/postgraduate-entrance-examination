# 参数方程的导数

$$
如：计算参数方程
\begin{cases}
x = acost ， \\
y = bsint
\end{cases}
所确定的函数 y = y(x) 的导数.
\\
\because \frac{dy}{dt} = \frac{d}{dt}(bsint) = bcost ， \frac{dx}{dt} = \frac{d}{dt}(acost) = -asint ，
\\
\therefore \frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{bcost}{-asint} .
$$

$$
如：计算参数方程
\begin{cases}
x = a(t - sint) ， \\
y = a(1 - cost)
\end{cases}
所确定的函数 y = y(x) 的二阶导数.
\\
\because \frac{dy}{dt} = \frac{d}{dt}(a(1 - cost)) = asint ， \frac{dx}{dt} = \frac{d}{dt}(a(t - sint)) = a(1 - cost) ，
\\
\therefore \frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{asint}{a(1 - cost)} = \frac{sint}{1 - cost} = cot\frac{t}{2} ，
\\
\therefore \frac{{d ^ 2}y}{dx ^ 2} = \frac{\frac{dy}{dx}}{dx} = \frac{\frac{\frac{dy}{dx}}{dt}}{\frac{dx}{dt}} = \frac{-\frac{1}{2}(csc\frac{t}{2}) ^ 2}{a(1 - cost)} .
$$



