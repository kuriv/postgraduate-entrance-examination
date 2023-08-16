# 洛必达法则

$$
定义： \lim_{x \to x_0}\frac{f(x)}{g(x)} = \lim_{x \to x_0}\frac{f(x)\prime}{f(x)\prime} .
\\
洛必达法则可用来求七种类型不定式的极限，即 \frac{0}{0} ， \frac{\infty}{\infty} ， \infty - \infty ， 0 \cdot \infty ， 1 ^ \infty ， \infty ^ 0 ， 0 ^ 0 ，
\\
其中前两种 \frac{0}{0} ， \frac{\infty}{\infty} 直接用洛必达法则，后五种 \infty - \infty (通分) ， 0 \cdot \infty (除倒数) ， 1 ^ \infty (取对数) ， \infty ^ 0 (恒等变形) ， 0 ^ 0 (恒等变形) 均可化为前两种.
$$

$$
如： \lim_{x \to 1}\frac{x ^ 3 - 3x + 2}{x ^ 3 - x ^ 2 - x + 1} .
\\
\because 直接将 x = 1 带入，此时分子分母均为 0 ，且原式为 \frac{0}{0}型，因此使用洛必达法则，
\\
\therefore \lim_{x \to 1}\frac{(x ^ 3 - 3x + 2)\prime}{(x ^ 3 - x ^ 2 - x + 1)\prime} = \lim_{x \to 1}\frac{3{x ^ 2} - 3}{3{x ^ 2} - 2x - 1} ，
\\
\because 直接将 x = 1 带入，此时分子分母也均为 0 ，且原式为 \frac{0}{0}型，因此继续使用洛必达法则，
\\
\therefore \lim_{x \to 1}\frac{(3{x ^ 2} - 3)\prime}{(3{x ^ 2} - 2x - 1)\prime} = \lim_{x \to 1}\frac{6x}{6x - 2} ，
\\
\because 直接将 x = 1 带入，此时原式为 \frac{6}{4} = \frac{3}{2} ，即 \lim_{x \to 1}\frac{x ^ 3 - 3x + 2}{x ^ 3 - x ^ 2 - x + 1} 的极限为 \frac{3}{2} .
$$

$$
如： \lim_{x \to 1}(1 - x ^ 2)tan\frac{\pi}{2}x .
\\
\because 直接将 x = 1 带入，此时原式为 0 \cdot \infty 型，因此先将原式转换为 \frac{0}{0} 型或\frac{\infty}{\infty} 型，再使用洛必达法则，
\\
\therefore \lim_{x \to 1}(1 - x ^ 2)tan\frac{\pi}{2}x = \lim_{x \to 1}\frac{(1 - x ^ 2)}{cot\frac{\pi}{2}x} ，
\\
\therefore \lim_{x \to 1}\frac{(1 - x ^ 2)\prime}{(cot\frac{\pi}{2}x)\prime} = \lim_{x \to 1}\frac{-2x}{-\frac{\pi}{2}(csc\frac{\pi}{2}x) ^ 2} ，
\\
\because 直接将 x = 1 带入，此时原式为 \frac{-2}{-\frac{\pi}{2}} = \frac{4}{\pi} ，即 \lim_{x \to 1}(1 - x ^ 2)tan\frac{\pi}{2}x 的极限为 \frac{3}{2} .
$$

$$
如： \lim_{x \to \infty}(x + \sqrt{1 + x ^ 2}) ^ \frac{1}{x} .
\\
\because 直接将 x = \infty 带入，此时原式为 \infty ^ 0 型，因此先将原式转换为 \frac{0}{0} 型或\frac{\infty}{\infty} 型，再使用洛必达法则，
\\
\therefore \lim_{x \to \infty}(x + \sqrt{1 + x ^ 2}) ^ \frac{1}{x} = \lim_{x \to \infty}e ^ {\frac{1}{x} \cdot \ln(x + \sqrt{1 + x ^ 2})} = \lim_{x \to \infty}e ^ {\frac{\ln(x + \sqrt{1 + x ^ 2})}{x}} ，
\\
\therefore \lim_{x \to \infty}\frac{(\ln(x + \sqrt{1 + x ^ 2}))\prime}{(x)\prime} = \lim_{x \to \infty}\frac{\frac{1}{\sqrt{1 + x ^ 2}}}{1} ，
\\
\because 直接将 x = \infty 带入，此时 \lim_{x \to \infty}\frac{\frac{1}{\sqrt{1 + x ^ 2}}}{1} 为 0 ，即原式为 \lim_{x \to \infty}e ^ 0 = 1 .
$$



