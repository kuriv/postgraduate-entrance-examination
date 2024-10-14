# 一阶微分方程求解

* [可分离变量型微分方程](#可分离变量型微分方程)
* [齐次型微分方程](#齐次型微分方程)
* [一阶线性微分方程](#一阶线性微分方程)
* [经典例题](#经典例题)

## 可分离变量型微分方程

$$
一般地，如果能把微分方程写成一端只含 dy 和 y 的函数，另一端只含 dx 和 x 的函数，那么原方程就称为可分离变量的微分方程.
\\
\frac{dy}{dx} = f(x)g(y) \Rightarrow \int{\frac{dy}{g(y)}} = \int{f(x)}dx .
$$

$$
形如 \frac{dy}{dx} = f(ax + by + c) 的方程，其中常数 a , b 全都不为零，解法为令 u = ax + by + c ，则 \frac{du}{dx} = a + b\frac{dy}{dx} ，代入原方程得 \frac{du}{dx} = a + bf(u) .
$$

## 齐次型微分方程

$$
形如 \frac{dy}{dx} = \phi(\frac{y}{x}) 的方程叫作齐次型微分方程，解法为令 \frac{y}{x} = u ，则 y = ux \Rightarrow \frac{dy}{dx} = \frac{du}{dx}x + u ，代入原方程得 \frac{du}{\phi(u) - u} = \frac{dx}{x} .
$$

## 一阶线性微分方程

$$
形如 y ^ {\prime} + p(x)y = q(x) 的方程叫作一阶线性微分方程，其中 p(x) ， q(x) 为已知的连续函数，其通解公式为 y = e ^ {-\int{p(x)}dx}[\int{e ^ {\int{p(x)}dx} \cdot q(x)}dx + C] .
$$

## 经典例题

$$
已知曲线通过点 (1 , 2) ，且在该曲线上任一点 M (x , y) 处的切线的斜率为 2x ，求该曲线的方程.\
\\
\because \frac{dy}{dx} = 2x ，且当 x = 1 时， y = 2 ，
\\
\therefore \frac{dy}{dx} = 2x \Rightarrow dy = 2xdx \Rightarrow \int{}dy = \int{2x}dx \Rightarrow y = x ^ 2 + C ，
\\
\therefore C = 1 ，
\\
\therefore 该曲线方程为 x ^ 2 + 1 .
$$

$$
已知曲线 y = f(x) 过点 (0 , -\frac{1}{2}) ，且其上任一点 (x , y) 处的切线斜率为 x\ln(1 + x ^ 2) ，求 f(x) .
\\
\because \frac{dy}{dx} = x\ln(1 + x ^ 2) ，且当 x = 0 时， y = -\frac{1}{2} ，
\\
\therefore \frac{dy}{dx} = x\ln(1 + x ^ 2) \Rightarrow dy = x\ln(1 + x ^ 2)dx \Rightarrow \int{}dy = \int{x\ln(1 + x ^ 2)}dx \Rightarrow y = \frac{1}{2}(1 + x ^ 2)[\ln(1 + x ^ 2) - 1] + C ，
\
\\
\therefore C = 0 ，
\\
\therefore f(x) = \frac{1}{2}(1 + x ^ 2)[\ln(1 + x ^ 2) - 1] .
$$

$$
求微分方程 \frac{ydy}{1 + y ^ 2} = \frac{dx}{x(1 + x ^ 2)} 的解.
\\
\because \int{\frac{y}{1 + y ^ 2}}dy = \int{\frac{1}{x(1 + x ^ 2)}}dx \Rightarrow \frac{1}{2}\ln(1 + y ^ 2) = \ln{|x|} - \frac{1}{2}\ln(1 + x ^ 2) + \ln{C}
\\
\Rightarrow \frac{1}{2}\ln(1 + y ^ 2) + \frac{1}{2}\ln(1 + x ^ 2) = \ln{|x|}  + \ln{C} \Rightarrow \frac{1}{2}\ln{[(1 + x ^ 2)(1 + y ^ 2)]} = \ln{|x|}  + \ln{C} \Rightarrow \ln{[(1 + x ^ 2)(1 + y ^ 2)]} = 2\ln{|x|} + \ln{C}
\\
\Rightarrow \ln{[(1 + x ^ 2)(1 + y ^ 2)]} = \ln{x ^ 2} + \ln{C} \Rightarrow (1 + x ^ 2)(1 + y ^ 2) = C{x ^ 2} .
$$

$$
求微分方程 dy = \sin{(x + y + 100)}dx 的通解.
\\
\because dy = \sin{(x + y + 100)}dx \Rightarrow \frac{dy}{dx} = \sin{(x + y + 100)} ，
\\
令 u = x + y + 100 ，则 \frac{du}{dx} = 1 + \frac{dy}{dx} \Rightarrow \frac{du}{dx} = 1 + \sin{u} \Rightarrow \frac{du}{1 + \sin{u}} = dx ，
\\
\therefore \frac{du}{1 + \sin{u}} = dx \Rightarrow \int{\frac{1}{1 + \sin{u}}}du = \int{}dx \Rightarrow \int{\frac{1 - \sin{u}}{1 - \sin ^ {2} {u}}}du = x + C \Rightarrow \tan{u} - \sec{u} = x + C ，
\\
\therefore 原方程通解为 \tan{(x + y + 100)} - \sec{(x + y + 100)} = x + C .
$$

$$
设 L 是一条平面曲线，其上任意一点 P (x , y) (x \gt 0) 到坐标原点的距离恒等于该点处的切线在 y 轴上的截距，且 L 经过点 (\frac{1}{2} , 0) ，求曲线 L 的方程.
\\
\because 设曲线 L 过点 P (x , y) 的切线方程为 Y - y = \frac{dy}{dx}(X - x) ，令 X = 0 ，则 Y = y - x\frac{dy}{dx} ，
\\
\therefore \sqrt{x ^ 2 + y ^ 2} = y - x\frac{dy}{dx} \Rightarrow \sqrt{1 + (\frac{y}{x}) ^ 2} = \frac{y}{x} - \frac{dy}{dx} ，
\\
令 u = \frac{y}{x} ，则 y = ux ， \frac{dy}{dx} = x\frac{du}{dx} + u ，
\\
\therefore \sqrt{1 + u ^ 2} = u - x\frac{du}{dx} - u \Rightarrow \frac{du}{\sqrt{1 + u ^ 2}} = -\frac{dx}{x} ，
\\
\therefore \int{\frac{1}{\sqrt{1 + u ^ 2}}}du = -\int{\frac{1}{x}}dx \Rightarrow \ln{(u + \sqrt{u ^ 2 + 1})} = -\ln{x} + \ln{C} \Rightarrow u + \sqrt{u ^ 2 + 1} = \frac{C}{x} \Rightarrow \frac{y}{x} + \sqrt{(\frac{y}{x}) ^ 2 + 1} = \frac{C}{x} \Rightarrow y + \sqrt{x ^ 2 + y ^ 2} = C ，
\\
\therefore C = \frac{1}{2} ，
\\
\therefore 曲线 L 的方程为 y + \sqrt{y ^ 2 + x ^ 2} = \frac{1}{2} ，即 y = \frac{1}{4} - x ^ 2 .
$$

$$
设 y = y(x) 是微分方程 y ^ {\prime} + y = e ^ {-x}\cos{x} 满足 y(0) = 0 的特解，求 y(x) .
\\
\because y = e ^ {-\int{p(x)}dx}[\int{e ^ {\int{p(x)}dx} \cdot q(x)}dx + C] \Rightarrow y = e ^ {-x}(\int{\cos{x}}dx + C) \Rightarrow y = e ^ {-x}(\sin{x} + C) ，
\\
\therefore C = 0 ，
\\
\therefore y(x) = e ^ {-x}{\sin{x}} .
$$

$$
求微分方程 ydx + (x - 3{y ^ 2})dy = 0 满足条件 y|_{x = 1} = 1 的解.
\\
\because ydx + (x - 3{y ^ 2})dy = 0 \Rightarrow ydx + xdy - 3{y ^ 2}dy = 0 \Rightarrow \frac{dx}{dy} + \frac{x}{y} - 3y = 0 \Rightarrow \frac{dx}{dy} + \frac{1}{y}x = 3y ，
\\
\therefore x = e ^ {-\int{p(y)}dy}[\int{e ^ {\int{p(y)}dy} \cdot q(y)}dy + C] \Rightarrow x = \frac{1}{y}(\int{y \cdot 3y}dy + C) \Rightarrow x = \frac{1}{y}(y ^ 3 + C) \Rightarrow x = y ^ 2 + \frac{C}{y} ，
\
\\
\therefore C = 0 ，
\\
\therefore x = y ^ 2 ， y = \sqrt{x} .
$$

$$
设函数 y = \phi(x) 是微分方程 y ^ {\prime} + ey = (1 - \frac{1}{x}) ^ x 的一个解，求 \lim_{x \to +\infty} {\phi(x)} .
\\
\because y = e ^ {-\int{p(x)}dx}[\int{e ^ {\int{p(x)}dx} \cdot q(x)}dx + C] = e ^ {-\int{e}dx}[\int{e ^ {\int{e}dx} \cdot (1 - \frac{1}{x}) ^ x}dx + C] = e ^ {-ex}[\int{e ^ {ex} \cdot (1 - \frac{1}{x}) ^ x}dx + C]
\\
= e ^ {-ex}[\int_{x_0} ^ {x}{e ^ {et} \cdot (1 - \frac{1}{t}) ^ t}dt + C] = \frac{\int_{x_0} ^ {x}{e ^ {et} \cdot (1 - \frac{1}{t}) ^ t}dt + C}{e ^ {ex}} ，
\\
\therefore \lim_{x \to +\infty} {\frac{\int_{x_0} ^ {x}{e ^ {et} \cdot (1 - \frac{1}{t}) ^ t}dt + C}{e ^ {ex}}} = \lim_{x \to +\infty} {\frac{e ^ {ex} \cdot (1 - \frac{1}{x}) ^ {x}}{e ^ {ex} \cdot e}} = \lim_{x \to +\infty} {\frac{e ^ {ex} \cdot e ^ {-1}}{e ^ {ex} \cdot e}} = \frac{1}{e ^ 2} .
$$



