# 一阶微分方程求解

* [可分离变量型微分方程](#可分离变量型微分方程)
* [齐次型微分方程](#齐次型微分方程)
* [一阶线性微分方程](#一阶线性微分方程)
* [伯努利方程](#伯努利方程)
* [二阶可降阶微分方程](#二阶可降阶微分方程)
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

## 伯努利方程

$$
形如 \frac{dy}{dx} + p(x)y = q(x){y ^ n} (n \neq 0 , 1) 的方程叫作伯努利方程，其中 p(x) ， q(x) 为已知的连续函数，
\\
其解法为先变形为 y ^ {-n}\frac{dy}{dx} + p(x){y ^ {1 - n}} = q(x) ，再令 z = y ^ {1 - n} ，得 \frac{dz}{dx} = (1 - n){y ^ {-n}}\frac{dy}{dx} ，则 \frac{1}{1 - n}\frac{dz}{dx} + p(x){z} = q(x) ，解此一阶线性微分方程即可.
$$

## 二阶可降阶微分方程

$$
形如 y ^ {\prime\prime} = f(x , y ^ {\prime}) (不显含未知函数 y) 的方程解法为先令 y ^ {\prime} = p ， y ^ {\prime\prime} = p ^ {\prime} ，则原方程变为一阶方程 \frac{dp}{dx} = f(x , p) ，
\
\\
若求得其通解为 p = \phi(x , C_1) ，即 y ^ {\prime} = \phi(x , C_1) ，则原方程的通解为 y = \int{\phi(x , C_1)}dx + C_2 .
$$

$$
形如 y ^ {\prime\prime} = f(y , y ^ {\prime}) (不显含未知函数 x) 的方程解法为先令 y ^ {\prime} = p ， y ^ {\prime\prime} = \frac{dp}{dx} = \frac{dp}{dy}\frac{dy}{dx} = \frac{dp}{dy}p ，则原方程变为一阶方程 p\frac{dp}{dy} = f(y , p) ，
\\
若求得其通解为 p = \phi(y , C_1) ，则由 p = \frac{dp}{dx} 可得 \frac{dy}{dx} = \phi(y , C_1) ，分离变量得 \frac{dy}{\phi(y , C_1)} = dx ，两边积分得 \int{\frac{1}{\phi(y , C_1)}}dy = x + C_2 .
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

$$
求 ydx = (1 + x\ln{y})xdy (y \gt 0) 的通解.
\\
\because ydx = (1 + x\ln{y})xdy \Rightarrow \frac{dx}{dy} = \frac{(1 + x\ln{y})x}{y} \Rightarrow \frac{dx}{dy} = \frac{x + {x ^ 2}\ln{y}}{y} \Rightarrow \frac{dx}{dy} - \frac{1}{y}x = \frac{\ln{y}}{y}{x ^ 2} \Rightarrow {x ^ {-2}}\frac{dx}{dy} - \frac{1}{y}{x ^ {-1}} = \frac{\ln{y}}{y} ，
\\
令 z = {x ^ {-1}} ，则 \frac{dz}{dy} = -\frac{1}{x ^ 2}\frac{dx}{dy} ，
\\
\therefore \frac{dz}{dy} + \frac{1}{y}z = -\frac{\ln{y}}{y} ，
\\
\therefore z = x ^ {-1} = e ^ {-\int{p(y)}dy}[\int{e ^ {\int{p(y)}dy} \cdot q(y)}dx + C] = e ^ {-\int{\frac{1}{y}}dy}[\int{e ^ {\int{\frac{1}{y}}dy} \cdot -\frac{\ln{y}}{y}}dy + C] = \frac{1}{y}[\int{-\ln{y}}dy + C] = \frac{1}{y}[y(1 - \ln{y}) + C] ，
\\
\therefore 通解为 \frac{1}{x} = 1 - \ln{y} + \frac{C}{y} .
$$

$$
求微分方程 y ^ {\prime\prime} = {y ^ {\prime}}[1 + (y ^ {\prime}) ^ 2] 满足 y(0) = 0 ， y ^ {\prime} (0) = 1 的特解.
\\
令 y ^ {\prime} = p ，则 y ^ {\prime\prime} = p ^ {\prime} ，
\\
\therefore y ^ {\prime\prime} = {y ^ {\prime}}[1 + (y ^ {\prime}) ^ 2] \Rightarrow p ^ {\prime} = p(1 + p ^ 2) \Rightarrow \frac{dp}{dx} = p(1 + p ^ 2) \Rightarrow \frac{dp}{p(1 + p ^ 2)} = dx \Rightarrow \ln{\frac{p ^ 2}{1 + p ^ 2}} = 2x + \ln{C_1} ，
\\
\therefore C_1 = \frac{1}{2} ，
\\
\therefore y ^ {\prime} = p = \sqrt{\frac{e ^ {2x}}{2 - e ^ {2x}}} = \frac{e ^ x}{\sqrt{2 - e ^ {2x}}} ，
\\
\therefore y = \int{\frac{e ^ x}{\sqrt{2 - e ^ {2x}}}}dx = \int{\frac{e ^ x}{\sqrt{2}\sqrt{1 - \frac{e ^ {2x}}{2}}}}dx = \int{\frac{\frac{e ^ x}{\sqrt{2}}}{\sqrt{1 - \frac{e ^ {2x}}{2}}}}dx = \int{\frac{\frac{e ^ x}{\sqrt{2}}}{\sqrt{1 - (\frac{e ^ {x}}{\sqrt{2}}) ^ 2}}}dx = \arcsin{\frac{e ^ x}{\sqrt{2}}} + C_2 ，
\\
\therefore C_2 = -\frac{\pi}{4} ，
\\
\therefore y = \arcsin{\frac{e ^ x}{\sqrt{2}}} -\frac{\pi}{4} .
$$

$$
求微分方程 y{y ^ {\prime\prime}} - \frac{2}{3}(y ^ {\prime}) ^ 2 = 0 满足 y(0) = 0 的解.
\\
令 y ^ {\prime} = p ，则 y ^ {\prime\prime} = \frac{dp}{dy}p ，
\\
\therefore y{y ^ {\prime\prime}} - \frac{2}{3}(y ^ {\prime}) ^ 2 = 0 \Rightarrow y\frac{dp}{dy}p - \frac{2}{3}{p ^ 2} = 0 \Rightarrow \frac{dp}{p} = \frac{2}{3}\frac{dy}{y} ，
\\
\therefore \int{\frac{1}{p}}dp = \frac{2}{3}\int{\frac{1}{y}}dy \Rightarrow \ln{p} = \frac{2}{3}\ln{y} + \ln{C_1} \Rightarrow p = C_1{y ^ {\frac{2}{3}}} ，
\\
\therefore \frac{dy}{y ^ {\frac{2}{3}}} = {C_1}dx \Rightarrow \int{y ^ {-\frac{2}{3}}}dy = \int{C_1}dx \Rightarrow 3{y ^ {\frac{1}{3}}} = {C_1}x + C_2 ，
\\
\therefore C_2 = 0 ，
\\
\therefore y = C_3{x ^ 3} .
$$



