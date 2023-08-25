# 泰勒公式

$$
带有佩亚诺余项的麦克劳林公式： f(x) = f(0) + f(0)\prime{x} + \frac{f(0)\prime\prime}{2!}x ^ 2 + \cdots + \frac{f(0) ^ {(n)}}{n!}x ^ n + o(x ^ n) .
$$

$$
带有拉格朗日余项的麦克劳林公式： f(x) = f(0) + f(0)\prime{x} + \frac{f(0)\prime\prime}{2!}x ^ 2 + \cdots + \frac{f(0) ^ {(n)}}{n!}x ^ n + \frac{f(\theta{x}) ^ {(n + 1)}}{(n + 1)!}x ^ {n + 1} (0 \lt \theta \lt 1) .
$$

$$
如：写出函数 f(x) = e ^ x 的带有拉格朗日余项的 n 阶麦克劳林公式.
\\
\because f(x)\prime = f(x)\prime\prime = \cdots f(x) ^ {(n)} = e ^ x ，
\\
\therefore f(0) = f(0)\prime = f(0)\prime\prime = \cdots f(0) ^ {(n)} = 1 ，
\\
\therefore \frac{f(\theta{x}) ^ {(n + 1)}}{(n + 1)!}x ^ {n + 1} = \frac{e ^ {\theta{x}}}{(n + 1)!}x ^ {n + 1} (0 \lt \theta \lt 1) ，
\\
带入朗格朗日余项的麦克劳林公式，得： e ^ x = 1 + x + \frac{1}{2!}x ^ 2 + \cdots + \frac{1}{n!}x ^ n + \frac{e ^ {\theta{x}}}{(n + 1)!}x ^ {n + 1} (0 \lt \theta \lt 1) .
$$

$$
如：求 f(x) = sinx 的带有拉格朗日余项的 n 阶麦克劳林公式.
\\
\because f(x)\prime = cosx ， f(x)\prime\prime = -sinx ， f(x)\prime\prime\prime = -cosx ， f(x) ^ {(4)} = sinx ， \cdots ， f(x) ^ {(n)} = sin(x + \frac{n}{2}\pi) ，
\\
\therefore f(0) = 0 ， f(0)\prime = 1 ， f(0)\prime\prime = 0 ， f(0)\prime\prime\prime = -1 ， f(0) ^ {(4)} = 0 ，
\\
令 n = 2m ，则 f(0) ^ {(n - 1)} = (-1) ^ {m - 1} \cdot \frac{1}{(2m - 1)!}x ^ {2m - 1} ， 且 f(0) ^ {(n)} = 0 ，
\\
\therefore \frac{f(\theta{x}) ^ {(n + 1)}}{(n + 1)!}x ^ {n + 1} = R_{2m}(x) ，
\\
带入拉格朗日余项的麦克劳林公式，得： sinx = x - \frac{1}{3!}x ^ 3 + \frac{1}{5!}x ^ 5 +- \cdots + (-1) ^ {m - 1} \cdot \frac{1}{(2m - 1)!}x ^ {2m - 1} + R_{2m}(x) .
$$

$$
利用带有佩亚诺余项的麦克劳林公式，求极限 \lim_{x \to 0}\frac{sinx - xcosx}{(sinx) ^ 3} .
\\
由等价无穷小，得： sinx ～ x ，则 (sinx) ^ 3 ～ x ^ 3 ，
\\
\because sinx = x - \frac{1}{3!}x ^ 3 + o(x ^ 3) ， xcosx = x - \frac{1}{2!}x ^ 3 + o(x ^ 3) ，
\\
\therefore sinx - xcosx = (x - \frac{1}{3!}x ^ 3 + o(x ^ 3)) - (x - \frac{1}{2!}x ^ 3 + o(x ^ 3)) = \frac{1}{3}x ^ 3 + o(x ^ 3) ，
\\
\therefore \lim_{x \to 0}\frac{sinx - xcosx}{(sinx) ^ 3} = \frac{\frac{1}{3}x ^ 3 + o(x ^ 3)}{x ^ 3} = \frac{1}{3} .
$$



