# 第二类换元法

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)
  * [例题四](#例题四)
  * [例题五](#例题五)
  * [例题六](#例题六)


## 定理内容

$$
设 x = \psi(t) 是单调的可导函数，并且 \psi(t) \neq 0 ，又设 f[\psi(t)]\psi(t)\prime 具有原函数，则有换元公式
\\
\int{f(x)}dx = [\int{f[\psi(t)]\psi(t)\prime}dt]_{t = \psi(x) ^ {-1}} ， 其中 \psi(x) ^ {-1} 是 x = \psi(t)的反函数.
$$

$$
如果被积函数含有 \sqrt{a ^ 2 - x ^ 2} ，可以作代换 x = a\sin{t} 化去根式，见例题一.
\\
如果被积函数含有 \sqrt{x ^ 2 + a ^ 2} ，可以作代换 x = a\tan{t} 化去根式，见例题二.
\\
如果被积函数含有 \sqrt{x ^ 2 - a ^ 2} ，可以作代换 x = \pm{a\sec{t}} 化去根式，见例题三.
$$

## 经典例题

### 例题一

$$
求 \int{\sqrt{a ^ 2 - x ^ 2}}dx .
\\
令 x = a\sin{t} ， -\frac{\pi}{2} \lt t \lt \frac{\pi}{2} ，则 \sqrt{a ^ 2 - x ^ 2} = \sqrt{{a ^ 2} - {a ^ 2}{(\sin{t}) ^ 2}} = \sqrt{a ^ 2(1 - (\sin{t}) ^ 2)} = \sqrt{{a ^ 2}{(\cos{t}) ^ 2}} = a\cos{t} ， d(x) = {a\cos{t}}dt ，
\\
\int{\sqrt{a ^ 2 - x ^ 2}}dx = \int{a\cos{t} \cdot a\cos{t}}dt = a ^ 2\int{(\cos{t}) ^ 2}dt = \frac{a ^ 2}{2}\int{(1 + \cos{2t})}dt = \frac{a ^ 2}{2}\int{1}dt + \frac{a ^ 2}{2}\int{\cos{2t}}dt = \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}\int{\cos{2t}}d(2t)
\\
= \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}\sin{2t} + C = \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}(2\sin{t}\cos{t}) + C ，
\\
\because x = a\sin{t} ，则 \sin{t} = \frac{x}{a} ， t = \arcsin{\frac{x}{a}} ， \cos{t} = \frac{\sqrt{a ^ 2 - x ^ 2}}{x} ，
\\
\therefore \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}(2\sin{t}\cos{t}) + C = \frac{a ^ 2}{2}\arcsin{\frac{x}{a}} + \frac{a ^ 2}{4}(2 \cdot \frac{x}{a} \cdot \frac{\sqrt{a ^ 2 - x ^ 2}}{x}) + C = \frac{a ^ 2}{2}\arcsin{\frac{x}{a}} + \frac{1}{2}x\sqrt{a ^ 2 - x ^ 2} + C .
$$

### 例题二

$$
求 \int{\frac{dx}{\sqrt{x ^ 2 + a ^ 2}}} .
\\
令 x = a\tan{t} ， -\frac{\pi}{2} \lt t \lt \frac{\pi}{2} ，则 \sqrt{x ^ 2 + a ^ 2} = \sqrt{{a ^ 2}{(\tan{t}) ^ 2} + a ^ 2} = \sqrt{a ^ 2(1 + (\tan{t}) ^ 2)} = \sqrt{{a ^ 2}{(\sec{t}) ^ 2}} = a\sec{t} ， d(x) = {a(\sec{t}) ^ 2}dt ，
\\
\int{\frac{dx}{\sqrt{x ^ 2 + a ^ 2}}} = \int{\frac{1}{a\sec{t}} \cdot a(\sec{t}) ^ 2}dt = \int{\sec{t}}dt = \ln ^ {|\sec{t} + \tan{t}|} + C ，
\\
\because x = a\tan{t} ，则 \tan{t} = \frac{x}{a} ， \sec{x} = \frac{\sqrt{x ^ 2 + a ^ 2}}{a} ，
\\
\therefore \ln ^ {|\sec{t} + \tan{t}|} + C = \ln ^ {(\frac{x}{a} + \frac{\sqrt{x ^ 2 + a ^ 2}}{a})} + C = \ln ^ {x + \sqrt{x ^ 2 + a ^ 2}} + C .
$$

### 例题三

$$
求 \int{\frac{dx}{\sqrt{x ^ 2 - a ^ 2}}} .
\\
令 x = a\sec{t} ， 0 \lt t \lt \frac{\pi}{2} ，则 \sqrt{x ^ 2 - a ^ 2} = \sqrt{{a ^ 2}{(\sec{t}) ^ 2} - a ^ 2} = \sqrt{a ^ 2((\sec{t}) ^ 2 - 1)} = \sqrt{{a ^ 2}{(\tan{t}) ^ 2}} = a\tan{t} ， d(x) = a\sec{t}\tan{t}dt ，
\\
\int{\frac{dx}{\sqrt{x ^ 2 - a ^ 2}}} = \int{\frac{1}{a\tan{t}} \cdot a\sec{t}\tan{t}}dt = \int{\sec{t}}dt = \ln ^ {|\sec{t} + \tan{t}|} + C ，
\\
\because x = a\sec{t} ，则 \sec{t} = \frac{x}{a} ， \tan{t} = \frac{\sqrt{x ^ 2 - a ^ 2}}{a} ，
\\
\therefore \ln ^ {|\sec{t} + \tan{t}|} + C = \ln ^ {\frac{x}{a} + \frac{\sqrt{x ^ 2 - a ^ 2}}{a}} + C = \ln ^ {x + \sqrt{x ^ 2 - a ^ 2}} + C .
$$

### 例题四

$$
求 \int{\frac{\sqrt{a ^ 2 - x ^ 2}}{x ^ 4}}dx .
\\
令 x = \frac{1}{t} ，则 d(x) = -\frac{1}{t ^ 2}dt ， \int{\frac{\sqrt{a ^ 2 - x ^ 2}}{x ^ 4}}dx = \int{\frac{\sqrt{a ^ 2 - \frac{1}{t ^ 2}}}{\frac{1}{t ^ 4}} \cdot -\frac{1}{t ^ 2}}dt = -\int{\sqrt{{a ^ 2}{t ^ 2} - 1}|t|}dt ，
\\
\because 当 a \gt 0 时， -\int{\sqrt{{a ^ 2}{t ^ 2} - 1}|t|}dt = -\int{\sqrt{{a ^ 2}{t ^ 2} - 1}t}dt = -\frac{1}{2a ^ 2}\int{\sqrt{{a ^ 2}{t ^ 2} - 1}}d({a ^ 2}{t ^ 2} - 1) = -\frac{1}{2a ^ 2} \cdot \frac{2}{3}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C
\\
= -\frac{1}{3a ^ 2}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C ，
\\
\because x = \frac{1}{t} ，则 t = \frac{1}{x} ，
\\
\therefore -\frac{1}{3a ^ 2}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C = -\frac{({a ^ 2}{\frac{1}{x ^ 2}} - 1) ^ {\frac{3}{2}}}{3a ^ 2} + C = -\frac{(a ^ 2 - x ^ 2) ^ \frac{3}{2}}{3{a ^ 2}{x ^ 3}} ，
\\
当 a \lt 0 时，有相同的结果.
$$

### 例题五

$$
求 \int{\frac{dx}{\sqrt{4x ^ 2 + 9}}} .
\\
\int{\frac{dx}{\sqrt{4x ^ 2 + 9}}} = \int{\frac{1}{\sqrt{(2x) ^ 2 + 3 ^ 2}}}dx = \frac{1}{2}\int{\frac{1}{\sqrt{(2x) ^ 2 + 3 ^ 2}}}d(2x) ，
\\
由公式得， \frac{1}{2}\int{\frac{1}{\sqrt{(2x) ^ 2 + 3 ^ 2}}}d(2x) = \ln ^ {2x + \sqrt{(2x) ^ 2 + 3 ^ 2}} + C = \ln ^ {2x + \sqrt{4x ^ 2 + 9}} + C .
$$

### 例题六

$$
求 \int{\frac{dx}{\sqrt{1 + x - x ^ 2}}} .
\\
\int{\frac{dx}{\sqrt{1 + x - x ^ 2}}} = \int{\frac{1}{\sqrt{\frac{\sqrt{5}}{2} ^ 2 - (x - \frac{1}{2}) ^ 2}}}dx = \int{\frac{1}{\sqrt{\frac{\sqrt{5}}{2} ^ 2 - (x - \frac{1}{2}) ^ 2}}}d(x - \frac{1}{2}) ，
\\
由公式得， \int{\frac{1}{\sqrt{\frac{\sqrt{5}}{2} ^ 2 - (x - \frac{1}{2}) ^ 2}}}d(x - \frac{1}{2}) = \arcsin{\frac{x - \frac{1}{2}}{\frac{\sqrt{5}}{2}}} + C = \arcsin{\frac{2x - 1}{\sqrt{5}}} + C .
$$



