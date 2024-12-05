# 全微分

* [定理内容](#定理内容)
* [必要条件](#必要条件)
* [充分条件](#充分条件)
* [判别步骤](#判别步骤)
* [经典例题](#经典例题)

## 定理内容

$$
设函数 z = f(x , y) 在点 (x , y) 的某实心邻域内有定义，若 z = f(x , y) 在该点的全增量 \Delta{z} = f(x + \Delta{x} , y + \Delta{y}) - f(x , y) 可表示为 A\Delta{x} + B\Delta{y} + o(\rho) ，
\\
其中 A ， B 仅与点 (x , y) 有关，而与 \Delta{x} ， \Delta{y} 无关，
\\
\rho = \sqrt{(\Delta{x}) ^ 2 + (\Delta{y}) ^ 2} ，且当 \Delta{x} \to 0 时， \Delta{y} \to 0 时， o(\rho) 为 \rho 的高阶无穷小，则称函数 z = f(x , y) 在点 (x , y) 处可微分，
\\
并称 A\Delta{x} + B\Delta{y} 为函数 z = f(x , y) 在点 (x , y) 处的全微分，记为 dz = A\Delta{x} + B\Delta{y} .
$$

## 必要条件

$$
若函数 z = f(x , y) 在点 (x , y) 处可微，则该函数在该点处的偏导数必存在，且 A = \frac{\partial{z}}{\partial{x}} ， B = \frac{\partial{z}}{\partial{y}} ，且全微分可记为 dz = \frac{\partial{z}}{\partial{x}}dx + \frac{\partial{z}}{\partial{y}}dy .
$$

## 充分条件

$$
若函数 z = f(x , y) 在点 (x , y) 处的偏导数存在且连续，则该函数在点 (x , y) 处可微.
$$

## 判别步骤

$$
先写出全增量 \Delta{z} = f(x_0 + \Delta{x} , y_0 + \Delta{y}) - f(x_0 , y_0) ，
\\
然后写出线性增量 A\Delta{x} + B\Delta{y} ，其中 A = f_x ^ {\prime} (x_0 , y_0) ， B = f_y ^ {\prime} (x_0 , y_0) ，
\\
最后作极限 \lim_{\Delta{x} \to 0 ， \Delta{y} \to 0} {\frac{\Delta{z} - (A\Delta{x} + B\Delta{y})}{\sqrt{(\Delta{x}) ^ 2 + (\Delta{y}) ^ 2}}} ，若该极限等于 0 ，则 z = f(x , y) 在点 (x_0 , y_0) 处可微.
$$

## 经典例题

$$
如：设 z_1 = |xy| ， z_2 =
\begin{cases}
\frac{x|y|}{\sqrt{x ^ 2 + y ^ 2}} ， (x , y) \neq (0 , 0) ， \\
0 ， (x , y) = (0 , 0) 
\end{cases}
判断 z_1 ， z_2 在点 (0 , 0) 处是否可微.
\\
\because \frac{\partial{z_1}}{\partial{x}}|(0 , 0) = \lim_{x \to 0} {\frac{z_1(x , 0) - z_1(0 , 0)}{x - 0}} = 0 ，
\\
\because \frac{\partial{z_1}}{\partial{y}}|(0 , 0) = \lim_{y \to 0} {\frac{z_1(0 , y) - z_1(0 , 0)}{y - 0}} = 0 ，
\\
\therefore \lim_{\Delta{x} \to 0 ， \Delta{y} \to 0} {\frac{\Delta{z} - (A\Delta{x} + B\Delta{y})}{\sqrt{(\Delta{x}) ^ 2 + (\Delta{x}) ^ 2}}} = \lim_{x \to 0 ， y \to 0} {\frac{z_1(x , y) - z_1(0 , 0) - \frac{\partial{z_1}}{\partial{x}}|(0 , 0) \cdot x - \frac{\partial{z_1}}{\partial{y}}|(0 , 0) \cdot y}{\sqrt{x ^ 2 + y ^ 2}}} = \lim_{x \to 0 ， y \to 0} {\frac{|xy|}{\sqrt{x ^ 2 + y ^ 2}}} ，
\\
由夹逼准则可得， 0 \le {\frac{|xy|}{\sqrt{x ^ 2 + y ^ 2}}} \le {\frac{\frac{x ^ 2 + y ^ 2}{2}}{\sqrt{x ^ 2 + y ^ 2}}} = \frac{\sqrt{x ^ 2 + y ^ 2}}{2} ,
\\
\because \lim_{x \to 0 ， y \to 0} {\frac{\sqrt{x ^ 2 + y ^ 2}}{2}} = 0 ，
\\
\therefore \lim_{x \to 0 ， y \to 0} {\frac{|xy|}{\sqrt{x ^ 2 + y ^ 2}}} = 0 ,
\\
\therefore z_1 在点 (0 , 0) 处可微.
\\
\because \frac{\partial{z_2}}{\partial{x}}|(0 , 0) = \lim_{x \to 0} {\frac{z_2(x , 0) - z_2(0 , 0)}{x - 0}} = 0 ，
\\
\because \frac{\partial{z_2}}{\partial{y}}|(0 , 0) = \lim_{y \to 0} {\frac{z_2(0 , y) - z_2(0 , 0)}{y - 0}} = 0 ，
\\
\therefore \lim_{\Delta{x} \to 0 ， \Delta{y} \to 0} {\frac{\Delta{z} - (A\Delta{x} + B\Delta{y})}{\sqrt{(\Delta{x}) ^ 2 + (\Delta{x}) ^ 2}}} = \lim_{x \to 0 ， y \to 0} {\frac{z_2(x , y) - z_2(0 , 0) - \frac{\partial{z_2}}{\partial{x}}|(0 , 0) \cdot x - \frac{\partial{z_2}}{\partial{y}}|(0 , 0) \cdot y}{\sqrt{x ^ 2 + y ^ 2}}} = \lim_{x \to 0 ， y \to 0} {\frac{\frac{x|y|}{\sqrt{x ^ 2 + y ^ 2}}}{\sqrt{x ^ 2 + y ^ 2}}}
\\
= \lim_{x \to 0 ， y \to 0} {\frac{x|y|}{x ^ 2 + y ^ 2}} ，
\\
\therefore z_2 在点 (0 , 0) 处不可微.
$$



