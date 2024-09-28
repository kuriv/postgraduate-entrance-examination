# 全微分

* [定理内容](#定理内容)
* [经典例题]

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

$$
可微的必要条件：若函数 z = f(x , y) 在点 (x , y) 处可微，则该函数在该点处的偏导数必存在，且 A = \frac{\partial{z}}{\partial{x}} ， B = \frac{\partial{z}}{\partial{y}} ，
\\
且全微分可记为 dz = \frac{\partial{z}}{\partial{x}}dx + \frac{\partial{z}}{\partial{y}}dy .
$$

$$
可微的充分条件：若函数 z = f(x , y) 在点 (x , y) 处的偏导数存在且连续，则该函数在点 (x , y) 处可微.
$$

## 经典例题