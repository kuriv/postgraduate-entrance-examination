# 变限积分的计算

* [定理内容](#定理内容)
* [重要结论](#重要结论)
* [经典例题](#经典例题)

## 定理内容

$$
设 F(x) = \int_{\phi_1(x)} ^ {\phi_2(x)}{f(t)}dt ，其中 f(x) 在 [a , b] 上连续，可导函数 \phi_1(x) 和 \phi_2(x) 的值域在 [a , b] 上，则有：
\\
F ^ {\prime} (x) = \frac{d}{dx}[\int_{\phi_1(x)} ^ {\phi_2(x)}{f(t)}dt] = f[\phi_2(x)]\phi_2 ^ {\prime} (x) - f[\phi_1(x)]\phi_1 ^ {\prime} (x) .
$$

## 重要结论

$$
f(x) 为可积的奇函数 \Rightarrow
\begin{cases}
\int_{0} ^ {x}{f(t)}dt 为偶函数， \\
\int_{a} ^ {x}{f(t)}dt 为偶函数 （a \neq 0） .
\end{cases}
$$

$$
f(x) 为可积的偶函数 \Rightarrow
\begin{cases}
\int_{0} ^ {x}{f(t)}dt 为奇函数， \\
\int_{a} ^ {x}{f(t)}dt （a \neq 0） \Rightarrow
\begin{cases}
若 \int_{a} ^ {x}{f(t)}dt = \int_{0} ^ {x}{f(t)}dt ，为奇函数， \\
若 \int_{a} ^ {x}{f(t)}dt \neq \int_{0} ^ {x}{f(t)}dt ，为非奇非偶函数.
\end{cases}
\end{cases}
$$

$$
f(x) 是可积的且以 T 为周期的周期函数，则 \ \int_{0} ^ {x}{f(t)}dt 是以 T 为周期的周期函数 \Leftarrow\Rightarrow \int_{0} ^ {T}{f(x)}dx = 0 .
$$

## 经典例题

$$
如：求曲线 y = \int_{0} ^ {\sin{x}}{e ^ {t ^ 2}}dt 在点 (0 , 0) 处的法线方程.
\\
\because y\prime = e ^ {\sin ^ {2} {x}} \cdot \cos{x} ， y\prime|_{x = 0} = 1 ，
\\
\therefore 切线斜率 k_1 = 1 ，法线斜率 k_2 = -1 ，
\\
\therefore 法线方程 y - 0 = -1(x - 0) ，即 y = -x .
$$



