# 有理函数积分

* [定理内容](#定理内容)
* [经典例题](#经典例题)


## 定理内容

$$
形如 \int{\frac{P_n(x)}{Q_m(x)}}dx (n \lt m) 的积分称为有理函数积分，其中 P_n(x) ， Q_m(x) 分别是 x 的 n 次多项式和 m 次多项式.
$$

## 经典例题

$$
求 \int{\frac{x + 1}{x ^ 2 - 5x + 6}}dx .
\\
令 \frac{x + 1}{x ^ 2 - 5x + 6} = \frac{A}{x - 3} + \frac{B}{x - 2} ，则 x + 1 = A(x - 2) + B(x - 3) ，
\\
\therefore 
\begin{cases}
A = 4 \\
B = -3 ，
\end{cases}
\\
\therefore \int{\frac{x + 1}{x ^ 2 - 5x + 6}}dx = \int{(\frac{4}{x - 3} - \frac{3}{x - 2})}dx = 4\ln{|x - 3|} - 3\ln{|x - 2|} + C .
$$

$$
求 \int{\frac{x + 2}{(2x + 1)(x ^ 2 + x + 1)}}dx .
\\
令 \frac{x + 2}{(2x + 1)(x ^ 2 + x + 1)} = \frac{A}{2x + 1} + \frac{Bx + C}{x ^ 2 + x + 1} ，则 x + 2 = A(x ^ 2 + x + 1) + (Bx + C)(2x + 1) ，
\\
\therefore
\begin{cases}
A = 2 \\
B = -1 \\
C = 0 ，
\end{cases}
\\
\therefore \int{\frac{x + 2}{(2x + 1)(x ^ 2 + x + 1)}}dx = \int{(\frac{2}{2x + 1} - \frac{x}{x ^ 2 + x + 1})}dx = \ln{|2x + 1|} - \frac{1}{2}\int{\frac{(2x + 1) - 1}{x ^ 2 + x + 1}}dx
\\
= \ln{|2x + 1|} - \frac{1}{2}\ln{|x ^ 2 + x + 1|} + \frac{1}{2}\int{\frac{1}{x ^ 2 + x + 1}}dx
\\
= \ln{|2x + 1|} - \frac{1}{2}\ln{|x ^ 2 + x + 1|} + \frac{1}{2}\int{\frac{1}{(x + \frac{1}{2}) ^ 2 + (\frac{\sqrt{3}}{2}) ^ 2}}dx = \ln{|2x + 1|} - \frac{1}{2}\ln{|x ^ 2 + x + 1|} + \frac{1}{2} \cdot \frac{1}{\frac{\sqrt{3}}{2}} \cdot \arctan{\frac{x + \frac{1}{2}}{\frac{\sqrt{3}}{2}}} + C
\\
= \ln{|2x + 1|} - \frac{1}{2}\ln{|x ^ 2 + x + 1|} + \frac{1}{\sqrt{3}}\arctan{\frac{2x + 1}{\sqrt{3}}} + C .
$$

$$
求 \int{\frac{x - 3}{(x - 1)(x ^ 2 - 1)}}dx .
\\
\because \frac{x - 3}{(x - 1)(x ^ 2 - 1)} = \frac{x - 3}{(x - 1) ^ 2(x + 1)} ，
\\
令 \frac{x - 3}{(x - 1) ^ 2(x + 1)} = \frac{Ax + B}{(x - 1) ^ 2} + \frac{C}{x + 1} ，则 x - 3 = (Ax + B)(x + 1) + C(x - 1) ^ 2 ，
\\
\therefore
\begin{cases}
A = 1 \\
B = -2 \\
C = -1 ，
\end{cases}
\\
\therefore \int{\frac{x - 3}{(x - 1)(x ^ 2 - 1)}}dx = \int{(\frac{x -2}{(x - 1) ^ 2} - \frac{1}{x + 1})}dx = \int{\frac{(x - 1) - 1}{(x - 1) ^ 2}}dx - \int{\frac{1}{x + 1}}dx = \int{[\frac{x - 1}{(x - 1) ^ 2} - \frac{1}{(x - 1) ^ 2}]}dx - \ln{|x + 1|}
\\
= \ln{|x - 1|} + \frac{1}{x - 1} - \ln{|x + 1|} + C .
$$

$$
求 \int{\frac{1 + \sin{x}}{\sin{x}(1 + \cos{x})}}dx .
\\
\because \frac{1 + \sin{x}}{\sin{x}(1 + \cos{x})} = \frac{1 + \frac{2\tan{\frac{x}{2}}}{1 + (\tan{\frac{x}{2}}) ^ 2}}{\frac{2\tan{\frac{x}{2}}}{1 + (\tan{\frac{x}{2}}) ^ 2}(1 + \frac{1 - (\tan{\frac{x}{2}}) ^ 2}{1 + (\tan{\frac{x}{2}}) ^ 2})}
\\
令 \tan{\frac{x}{2}} = u ， x = 2\arctan{u} ， d(x) = {\frac{2}{1 + u ^ 2}}du ，则 \int{\frac{1 + \frac{2\tan{\frac{x}{2}}}{1 + (\tan{\frac{x}{2}}) ^ 2}}{\frac{2\tan{\frac{x}{2}}}{1 + (\tan{\frac{x}{2}}) ^ 2}(1 + \frac{1 - (\tan{\frac{x}{2}}) ^ 2}{1 + (\tan{\frac{x}{2}}) ^ 2})}}dx = \int{\frac{1 + \frac{2u}{1 + u ^ 2}}{\frac{2u}{1 + u ^ 2}(1 + \frac{1 - u ^ 2}{1 + u ^ 2})} \cdot \frac{2}{1 + u ^ 2}}du
\\
= \frac{1}{2}\int{(u + 2 + \frac{1}{u})}du = \frac{1}{2}(\frac{1}{2}u ^ 2 + 2u + \ln{|u|}) + C = \frac{1}{4}u ^ 2 + u + \frac{1}{2}\ln{|u|} + C = \frac{1}{4}(\tan{\frac{x}{2}}) ^ 2 + \tan{\frac{x}{2}} + \frac{1}{2}\ln{|\tan{\frac{x}{2}}|} + C .
$$

$$
求 \int{\frac{\sqrt{x - 1}}{x}}dx .
\\
令 \sqrt{x - 1} = u ， 则 x = u ^ 2 + 1 ， d(x) = {2u}du ，
\\
\int{\frac{\sqrt{x - 1}}{x}}dx = \int{\frac{u}{u ^ 2 + 1}2u}du = 2\int{\frac{u ^ 2}{u ^ 2 + 1}}du = 2\int{(1 - \frac{1}{u ^ 2 + 1})}du = 2(u - \arctan{u}) + C = 2(\sqrt{x - 1} - \arctan{\sqrt{x - 1}}) + C .
$$

$$
求 \int{\frac{dx}{1 + \sqrt[3]{x + 2}}} .
\\
令 \sqrt[3]{x + 2} = u ，则 x = u ^ 3 - 2 ， d(x) = {3u ^ 2}du ，
\\
\int{\frac{dx}{1 + \sqrt[3]{x + 2}}} = \int{\frac{1}{1 + u}3u ^ 2}du = 3\int{\frac{(u ^ 2 - 1) + 1}{1 + u}}du = 3\int{(u - 1 + \frac{1}{1 + u})}du = 3(\frac{1}{2}u ^ 2\ - u + \ln|1 + u|) + C
\\
= 3(\frac{1}{2}\sqrt[3]{(x + 2) ^ 2} - \sqrt[3]{x + 2} + \ln{|1 + \sqrt[3]{x + 2}|}) + C = \frac{3}{2}\sqrt[3]{(x + 2) ^ 2} - 3\sqrt[3]{x + 2} + 3\ln{|1 + \sqrt[3]{x + 2}|}) + C .
$$

$$
求 \int{\frac{dx}{(1 + \sqrt[3]{x})\sqrt{x}}} .
\\
令 \sqrt[6]{x} = u ，则 x = u ^ 6 ， d(x) = {6u ^ 5}du ，
\\
\int{\frac{dx}{(1 + \sqrt[3]{x})\sqrt{x}}} = \int{\frac{1}{(1 + u ^ 2)u ^ 3}6u ^ 5}du = 6\int{\frac{u ^ 2}{1 + u ^ 2}}du = 6\int(1 - \frac{1}{1 + u ^ 2})du = 6(u - \arctan{u}) + C = 6(\sqrt[6]{x} - \arctan{\sqrt[6]{x}}) + C .
$$



