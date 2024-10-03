# 多元函数微分法则

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 z = f(u , v) ， u = \phi(x , y) ， v = \psi(x , y) ，则 z = f[\phi(x , y) , \psi(x , y)] ，且 \frac{\partial{z}}{\partial{x}} = \frac{\partial{z}}{\partial{u}}\frac{\partial{u}}{\partial{x}} + \frac{\partial{z}}{\partial{v}}\frac{\partial{v}}{\partial{x}} ， \frac{\partial{z}}{\partial{y}} = \frac{\partial{z}}{\partial{u}}\frac{\partial{u}}{\partial{y}} + \frac{\partial{z}}{\partial{v}}\frac{\partial{v}}{\partial{y}} .
$$

$$
设 z = f(u , v) ， u = \phi(t) ， v = \psi(t) ，则 z = f[\phi(t) , \psi(t)] ，且 \frac{\partial{z}}{\partial{t}} = \frac{\partial{z}}{\partial{u}}\frac{du}{dt} + \frac{\partial{z}}{\partial{v}}\frac{dv}{dt} .
$$

## 经典例题

$$
设 z = f({e ^ x}\sin{y} , x ^ 2 + y ^ 2) ，其中 f 具有二阶连续偏导数， f_1 ^ {\prime} (0 , 0) = 1 ， f_2 ^ {\prime} (0 , 0) = -1 ，求 \frac{\partial ^ {2} {z}}{\partial{x}\partial{y}}|_{(0 , 0)} .
\\
\because \frac{\partial{z}}{\partial{x}} = f_1 ^ {\prime} \cdot ({e ^ x}\sin{y})_{x} ^ {\prime} + f_2 ^ {\prime} \cdot (x ^ 2 + y ^ 2)_{x} ^ {\prime} = {e ^ x}\sin{y}f_1 ^ {\prime} + {2x}f_2 ^ {\prime} ，
\\
\therefore \frac{\partial ^ {2} {z}}{\partial{x}\partial{y}} = {e ^ x}\cos{y} \cdot f_1 ^ {\prime} + {e ^ x}\sin{y} \cdot (f_1 ^ {\prime})_{y} ^ {\prime} + 2x(f_2 ^ {\prime})_{y} ^ {\prime}
\\
= {e ^ x}\cos{y} \cdot f_1 ^ {\prime} + {e ^ x}\sin{y} \cdot [f_{11} ^ {\prime\prime} \cdot ({e ^ x}\sin{y})_{y} ^ {\prime} + f_{12} ^ {\prime\prime} \cdot (x ^ 2 + y ^ 2)_{y} ^ {\prime}] + 2x[f_{21} ^ {\prime\prime} \cdot ({e ^ x}\sin{y})_{y} ^ {\prime} + f_{22} ^ {\prime\prime} \cdot \ (x ^ 2 + y ^ 2)_{y} ^ {\prime}] ，
\\
\therefore \frac{\partial ^ {2} {z}}{\partial{x}\partial{y}}|_{(0 , 0)} = f_1 ^ {\prime} (0 , 0) = 1 .
$$

$$
设函数 f(x , e ^ x) = x + e ^ x ，且 f_1 ^ {\prime} (x , y)|_{y = e ^ x} = 1 + 2{e ^ x} ，求 f_2 ^ {\prime} (x , y)|_{y = e ^ x} .
\\
\
\
\because [f(x , e ^ x)]_{x} ^ {\prime} = f_1 ^ {\prime} (x , y)|_{y = e ^ x} + f_2 ^ {\prime} (x , y)|_{y = e ^ x} \cdot e ^ x = 1 + 2{e ^ x} + f_2 ^ {\prime} (x , y)|_{y = e ^ x} \cdot e ^ x = 1 + e ^ x ，
\\
\therefore f_2 ^ {\prime} (x , y)|_{y = e ^ x} \cdot e ^ x = -e ^ x ， f_2 ^ {\prime} (x , y)|_{y = e ^ x} = -1 .
$$

$$
设对任意的 x ， y 有 (\frac{\partial{f}}{\partial{x}}) ^ 2 + (\frac{\partial{f}}{\partial{y}}) ^ 2 = 4 ，用变量代换 x = uv ， y = \frac{u ^ 2 - v ^ 2}{2} 将函数 f(x , y) 变换成函数 g(u , v) ，
\\
且满足关系式 a(\frac{\partial{g}}{\partial{u}}) ^ 2 - b(\frac{\partial{g}}{\partial{v}}) ^ 2 = u ^ 2 + v ^ 2 ，求 a ， b .
\\
令 g(u , v) = f(uv , \frac{u ^ 2 - v ^ 2}{2}) ，
\\
\because \frac{\partial{g}}{\partial{u}} = \frac{\partial{f}}{\partial{x}} \cdot v + \frac{\partial{f}}{\partial{y}} \cdot u ， \frac{\partial{g}}{\partial{v}} = \frac{\partial{f}}{\partial{x}} \cdot u - \frac{\partial{f}}{\partial{y}} \cdot v ，
\\
\therefore a(\frac{\partial{g}}{\partial{u}}) ^ 2 - b(\frac{\partial{g}}{\partial{v}}) ^ 2 = a[v ^ 2(\frac{\partial{f}}{\partial{x}}) ^ 2 + u ^ 2(\frac{\partial{f}}{\partial{y}}) ^ 2 + 2uv\frac{\partial{f}}{\partial{x}}\frac{\partial{f}}{\partial{y}}] - b[u ^ 2(\frac{\partial{f}}{\partial{x}}) ^ 2 + v ^ 2(\frac{\partial{f}}{\partial{y}}) ^ 2 - 2uv\frac{\partial}{\partial{x}}\frac{\partial{f}}{\partial{y}}]
\\
= (a{v ^ 2} - b{u ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2 + (a{u ^ 2} - b{v ^ 2})(\frac{\partial{f}}{\partial{y}}) ^ 2 + 2(a + b)uv\frac{\partial{f}}{\partial{x}}\frac{\partial{f}}{\partial{y}} = u ^ 2 + v ^ 2 ，
\\
\therefore a + b = 0 ，
\\
\because (\frac{\partial{f}}{\partial{x}}) ^ 2 + (\frac{\partial{f}}{\partial{y}}) ^ 2 = 4 ，
\\
\therefore (\frac{\partial{f}}{\partial{y}}) ^ 2 = 4 - (\frac{\partial{f}}{\partial{x}}) ^ 2 ，
\\
\therefore (a{v ^ 2} - b{u ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2 + (a{u ^ 2} - b{v ^ 2})(\frac{\partial{f}}{\partial{y}}) ^ 2 = (a{v ^ 2} - b{u ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2 + (a{u ^ 2} - b{v ^ 2})[4 - (\frac{\partial{f}}{\partial{x}}) ^ 2]
\\
= (a{v ^ 2} - b{u ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2 + 4(a{u ^ 2} - b{v ^ 2}) - (a{u ^ 2} - b{v ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2
\\
= (a{v ^ 2} - b{u ^ 2} - a{u ^ 2} + b{v ^ 2})(\frac{\partial{f}}{\partial{x}}) ^ 2 + 4(a{u ^ 2} - b{v ^ 2})
\\
= (a + b)(v ^ 2 - u ^ 2)(\frac{\partial{f}}{\partial{x}}) ^ 2 + 4(a{u ^ 2} - b{v ^ 2}) = 4(a{u ^ 2} - b{v ^ 2}) = 4a{u ^ 2} - 4b{v ^ 2} = u ^ 2 + v ^ 2 ，
\\
\therefore 4a = 1 ， -4b = 1 ，
\\
\therefore a = \frac{1}{4} ， b = -\frac{1}{4} .
$$

$$
若函数 z = z(x , y) 由方程 e ^ {x + 2y + 3z} + xyz = 1 确定，求 dz|_{(0 , 0)} .
\\
当 x = 0 ， y = 0 时， e ^ {x + 2y + 3z} + xyz = e ^ {3z} = 1 ，
\\
\therefore z(0 , 0) = 0 ，
\\
方程两端同时求全微分可得， e ^ {x + 2y + 3z} \cdot {dx} + e ^ {x + 2y + 3z} \cdot {2dy} + e ^ {x + 2y + 3z} \cdot {3dz} + yz{dx} + xz{dy} + xy{dz}
\\
= e ^ {x + 2y + 3z}({dx} + {2dy} + {3dz}) + yz{dx} + xz{dy} + xy{dz} = 0 ，
\\
当 x = 0 ， y = 0 ， z = 0 时， {dx} + {2dy} + {3dz} = 0 ，
\\
\therefore dz|_{(0 , 0)} = -\frac{1}{3}{dx} - \frac{2}{3}{dy} .
$$



