# 基本性质

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
\iint_D{1}d\sigma = \iint_D{}d\sigma = A ，其中 A 为 D 的面积.
$$

$$
当 f(x , y) 在有界闭区间 D 上可积时， f(x , y) 在 D 上必有界.
$$

$$
设 k_1 ， k_2 为常数，则 \iint_D{[{k_1}f(x , y) \pm {k_2}g(x , y)]}d\sigma = k_1\iint_D{f(x , y)}d\sigma \pm k_2\iint_D{g(x , y)}d\sigma .
$$

$$
设 f(x , y) 在有界闭区间 D 上可积，且 D_1 \cup D_2 = D ， D_1 \cap D_2 = \varnothing ，则 \iint_D{f(x , y)}d\sigma = \iint_{D_1}{f(x , y)}d\sigma + \iint_{D_2}{f(x , y)}d\sigma .
$$

$$
当 f(x , y) ， g(x , y) 在有界闭区间 D 上可积时，若在 D 上有 f(x , y) \le g(x , y) ，则 \iint_D{f(x , y)}d\sigma \le \iint_D{g(x , y)}d\sigma .
$$

$$
设 M ， m 分别是 f(x , y) 在有界闭区域 D 上的最大值和最小值， A 为 D 的面积，则 mA \le \iint_D{f(x , y)}d\sigma \le MA .
$$

$$
设函数 f(x , y) 在有界闭区域 D 上连续， A 为 D 的面积，则在 D 上至少存在一点 (\xi , \eta) ，使得 \iint_D{f(x , y)}d\sigma = f(\xi , \eta)A .
$$

## 经典例题

$$
如：设 D_t = \{(x , y|2{x ^ 2} + 3{y ^ 2} \le 6t)\} (t \ge 0) ， f(x , y) =
\begin{cases}
\frac{\sqrt[3]{1 - (x ^ 2 + y ^ 2)} - 1}{e ^ {x ^ 2 + y ^ 2}} ， (x , y) \neq (0 , 0) ，
\\
a ， (x , y) = (0 , 0) ，
\end{cases}
为连续函数，令 F(t) = \iint_{D_t}{f(x , y)}dxdy ，求 F_{+} ^ {\prime} (0) .
\\
\because f(x , y) 为连续函数，
\\
\therefore \lim_{(x , y) \to (0 , 0)} f(x , y) = \lim_{(x , y) \to (0 , 0)} \frac{\sqrt[3]{1 - (x ^ 2 + y ^ 2)} - 1}{e ^ {x ^ 2 + y ^ 2}} = \lim_{(x , y) \to (0 , 0)} \frac{-\frac{1}{3}(x ^ 2 + y ^ 2)}{x ^ 2 + y ^ 2} = -\frac{1}{3} = a ，
\\
\therefore F_{+} ^ {\prime} (0) = \lim_{t \to 0} \frac{F(t) - F(0)}{t - 0} = \lim_{t \to 0} \frac{F(t)}{t} = \lim_{t \to 0} \frac{\iint_{D_t}{f(x , y)}dxdy}{t} = \lim_{t \to 0} \frac{\sqrt{6}\pi{t}f(\xi , \eta)}{t} ， 其中 (\xi , \eta) \in D_t ，
\\
\therefore \lim_{t \to 0} \frac{\sqrt{6}\pi{t}f(\xi , \eta)}{t} = -\frac{1}{3}\sqrt{6}\pi .
$$



