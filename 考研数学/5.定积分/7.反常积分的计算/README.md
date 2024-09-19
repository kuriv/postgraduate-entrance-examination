# 反常积分的计算

* [注意事项](#注意事项)
* [经典例题](#经典例题)

## 注意事项

$$
在计算反常积分时，注意识别奇点（端点、内部）.
$$

## 经典例题

$$
求 \int_{\frac{1}{2}} ^ {\frac{3}{2}}{\frac{1}{\sqrt{|x - x ^ 2|}}}dx .
\\
\because \int_{\frac{1}{2}} ^ {\frac{3}{2}}{\frac{1}{\sqrt{|x - x ^ 2|}}}dx = \int_{\frac{1}{2}} ^ {1}{\frac{1}{\sqrt{x - x ^ 2}}}dx + \int_{1} ^ {\frac{3}{2}}{\frac{1}{\sqrt{x ^ 2 - x}}}dx ，
\\
\int_{\frac{1}{2}} ^ {1}{\frac{1}{\sqrt{x - x ^ 2}}}dx = \int_{\frac{1}{2}} ^ {1}{\frac{1}{\sqrt{(\frac{1}{2}) ^ 2 - (x - \frac{1}{2}) ^ 2}}}dx = \arcsin{\frac{x - \frac{1}{2}}{\frac{1}{2}}}|_{\frac{1}{2}} ^ {1} = \arcsin(2x - 1)|_{\frac{1}{2}} ^ {1} = \arcsin{1} = \frac{\pi}{2} ，
\\
\int_{1} ^ {\frac{3}{2}}{\frac{1}{\sqrt{x ^ 2 - x}}}dx = \int_{1} ^ {\frac{3}{2}}{\frac{1}{\sqrt{(x - \frac{1}{2}) ^ 2 - (\frac{1}{2}) ^ 2}}}dx = \ln[(x - \frac{1}{2}) + \sqrt{(x - \frac{1}{2}) ^ 2 - (\frac{1}{2}) ^ 2}]|_{1} ^ {\frac{3}{2}} = \ln(1 + \frac{\sqrt{3}}{2}) - \ln\frac{1}{2} = \ln(2 + \sqrt{3}) ，
\\
\therefore \int_{\frac{1}{2}} ^ {\frac{3}{2}}{\frac{1}{\sqrt{|x - x ^ 2|}}}dx = \frac{\pi}{2} + \ln(2 + \sqrt{3}) .
$$

$$
求 \int_{3} ^ {+\infty}{\frac{1}{(x - 1) ^ 4\sqrt{x ^ 2 - 2x}}}dx .
\\
\because \int_{3} ^ {+\infty}{\frac{1}{(x - 1) ^ 4\sqrt{x ^ 2 - 2x}}}dx = \int_{3} ^ {+\infty}{\frac{1}{(x - 1) ^ 4\sqrt{(x - 1) ^ 2 - 1}}}dx ，
\\
令 (x - 1) = \sec{u} ，则 d(x) = \sec{u}\tan{u}du ，
\\
当 x = 3 时，可取 u = \frac{\pi}{3} ，当 x = \infty 时，可取 u = \frac{\pi}{2} ，
\\
\therefore \int_{3} ^ {+\infty}{\frac{1}{(x - 1) ^ 4\sqrt{(x - 1) ^ 2 - 1}}}dx = \int_{\frac{\pi}{3}} ^ {\frac{\pi}{2}}{\frac{1}{\sec ^ {4} {u} \sqrt{\sec ^ {2} {u} - 1}}}\sec{u}\tan{u}du = \int_{\frac{\pi}{3}} ^ {\frac{\pi}{2}}{\frac{1}{\sec ^ {3} {u}}}du = \int_{\frac{\pi}{3}} ^ {\frac{\pi}{2}}{\cos ^ {3} {u}}du
\\
= \int_{\frac{\pi}{3}} ^ {\frac{\pi}{2}}{\cos{x}(1 - \sin ^ {2} {x})}du = \int_{\frac{\pi}{3}} ^ {\frac{\pi}{2}}{(1 - \sin ^ {2} {x})}d(\sin{x}) = \sin{x}|_{\frac{\pi}{3}} ^ {\frac{\pi}{2}} - \frac{1}{3}\sin ^ {3} {x}|_{\frac{\pi}{3}} ^ {\frac{\pi}{2}} = \frac{2}{3} - \frac{3\sqrt{3}}{8} .
$$



