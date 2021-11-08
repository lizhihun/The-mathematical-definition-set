首先是同济高等数学第2006年版<br/>
版号：第六版<br/>
# 同济数学
## 上册<br/>
原函数定义<br/>
不定积分定义<br/>
定积分定义<br/>
反常积分定义<br/>
反常积分2定义<br/>
## 下册<br/>
二元函数定义<br/>
二重极限定义<br/>
二元函数的连续定义<br/>
间断点定义<br/>
偏导数定义<br/>
全微分定义<br/>
一元向量值函数定义<br/>
向量值函数的极限定义<br/>
向量值函数的导数定义<br/>
函数极值定义<br/>
二重积分定义<br/>
重积分定义<br/>
应用<br/>
第一类曲线积分<br/>
定义第二类曲线积分定义<br/>
第一类曲面积分定义<br/>
第二类曲面积分定义<br/>
无穷级数发散定义<br/>
函数项级数一致收敛的定义<br/>

## 定义集
### 映射：
定义<br/> 
设 $X 、 Y$ 是两个非空集合, 如果存在一个法则 $f$, 使得对 $X$ 中每个元 素 $x$, 按法则 $f$, 在 $Y$ 中有唯一确定的元素 $y$ 与之对应<br/>
则称<br/>
$f$ 为从 $X$ 到 $Y$ 的映 射<br/>
记作<br/>
$f: X \rightarrow Y$<br/>
其中<br/>
$y$ 称为元素 $x$ (在映射 $f$ 下)的像, 并记作 $f(x)$, 即$y=f(x)$,而元素 $x$ 称为元素 $y$ (在炴射 $f$ 下) 的一个原像; 集合 $X$ 称为咉射 $f$ 的定义域, 记作 $D_{I}$, 即 $D_{f}=X ; X$ 中所有元素的像所组成的集合称为映射 $f$ 的值域,记作 $R_{f}$ 或 $f(X)$, 即$R_{j}=f(X)=\{f(x) \mid x \in X\}$

### 函数的定义
定义<br/>
设数集 $D \subset \mathbf{R}$<br/>
则称映射 $f: D \rightarrow \mathbf{R}$ 为定义在 $D$ 上的函数,<br/>
通常简记为$y=f(x), x \in D$<br/>
其中<br/>
$x$ 称为自变量, $y$ 称为因变量, $D$ 称为定义域, 记作 $D_{f}$, 即 $D_{f}=D$.函数定义中, 对每个 $x \in D$, 按对应法则 $f$, 总有唯一确定的值 $y$ 与之对应, 这个值称为函数 $f$ 在 $x$ 处的函数值, 记作 $f(x)$, 即 $y=f(x)$. 因变量 $y$ 与自变 量 $x$ 之间的这种依赖关系,通常称为函数关系. 函数值 $f(x)$ 的全体所构成的集 合称为函数 $f$ 的值域,记作 $R_{f}$ 或 $f(D)$, 即$R_{f}=f(D)=\left\{y \mid y=f(x), x \in D^{\prime}\right\}$

### 数列的收敛定义
定义<br/>
设 $\left\{x_{n}\right\}$ 为一数列, 如果存在常数 $a$, 对于任意给定的正数 $\varepsilon$ (不论它 多么小), 总存在正整数 $N$,使得当 $n>N$ 时,不等式$\left|x_{n}-a\right|<\varepsilon$都成立, 
那么就称<br/>
常数 $a$ 是数列 $\left\{x_{n}\right\}$ 的极限, 或者称数列 $\left\{x_{n} \mid\right.$ 收敛于 $a$,
记为<br/>
$\lim _{n \rightarrow \infty} x_{n}=a,$或$x_{n} \rightarrow a(n \rightarrow \infty)$<br/>
如果不存在这样的常数 $a$,<br/>
就说<br/>
数列 $\left|x_{n}\right|$ 没有极限, 或者说数列 $\left|x_{n}\right|$ 是发散的, 习惯上也说 $\lim _{n \rightarrow \infty} x_{n}$ 不存在.

<!--### 极限定理
定理 1 (极限的唯一性) 如果数列 $\left\{x_{n}\right\}$ 收敛, 那么它的极限唯一.
证 用反证法. 假设同时有 $x_{n} \rightarrow a$ 及 $x_{n} \rightarrow b$, 且 $a<b .$ 取 $\varepsilon=\frac{b-a}{2}$. 因为 $\lim _{n \rightarrow \infty} x_{n}=a$, 故 $\exists$ 正整数 $N_{1}$, 当 $n>N_{1}$ 时, 不等式
$$
\left|x_{n}-a\right|<\frac{b-a}{2}
$$
都成立. 同理, 因为 $\lim _{n \rightarrow \infty} x_{n}=b$, 故 $\exists$ 正整数 $N_{2}$, 当 $n>N_{2}$ 时, 不等式
$$
\left|x_{n}-b\right|<\frac{b-a}{2}
$$
都成立. 取 $N=\max \left\{N_{1}, N_{2}\right\}$ (这式子表示 $N$ 是 $N_{1}$ 和 $N_{2}$ 中较大的那个数), 则 当 $n>N$ 时, $(2)$ 式及 $(3)$ 式会同时成立. 但由 $(2)$ 式有 $x_{n}<\frac{a+b}{2}$, 由 $(3)$ 式有 $x_{n}>\frac{a+b}{2}$, 这是不可能的. 这矛盾证明了本定理的断言.

### 数列定理
定理 2 (收敛数列的有界性) 如果数列 $\left\{x_{n}\right\}$ 收敛, 那么数列 $\left\{x_{n}\right\}$ 一定有界. 证 因为数列 $\left\{x_{n}\right\}$ 收玫, 设 $\lim _{n \rightarrow \infty} x_{n}=a$. 根据数列极限的定义, 对于 $\varepsilon=1$, $\exists$ 正整数 $N$, 当 $n>N$ 时,不等式
$$
\left|x_{n}-a\right|<1
$$
都成立. 于是, 当 $n>N$ 时,
$$
\left|x_{n}\right|=\left|\left(x_{n}-a\right)+a\right| \leqslant\left|x_{n}-a\right|+|a|<1+|a|
$$
取 $M=\max \left\{\left|x_{1}\right|,\left|x_{2}\right|, \cdots,\left|x_{N}\right|, 1+|a|\right\}$, 那么数列 $\left\{x_{n}\right\}$ 中的一切 $x_{n}$ 都满足 不等式
$$
\left|x_{n}\right| \leqslant M
$$
这就证明了数列 $\left\{x_{n}\right\}$ 是有界的.


定理 3(收敛数列的保号性) 如果 $\lim _{n \rightarrow \infty} x_{n}=a$, 且 $a>0$ (或 $a<0$ ), 那么存 在正整数 $N>0$, 当 $n>N$ 时, 都有 $x_{n}>0$ (或 $\left.x_{n}<0\right)$.


'定理 4(收敛数列与其子数列间的关系) 如果数列 $\left\{x_{n} \mid\right.$ 收玫于 $a$, 那么它 的任一子数列也收敛, 且极限也是 $a$.-->

### 函数的极限定义
定义 1<br/>
设函数 $f(x)$ 在点 $x_{0}$ 的某一去心邻域内有定义. 如果存在常数 $A$, 对于任意给定的正数 $\varepsilon$ (不论它多么小), 总存在正数 $\delta$, 使得当 $x$ 满足不等式 $0<\left|x-x_{10}\right|<\delta$ 时, 对应的函数值 $f(x)$ 都满足不等式$|f(x)-A|<\varepsilon$
那么常数 $A$ 就叫做<br/>
函数 $f(x)$ 当 $x \rightarrow x_{0}$ 时的极限,<br/>
记作<br/>
$\lim _{x \rightarrow x_{0}} f(x)=A \text { 或 } f(x) \rightarrow A\left(\text { 当 } x \rightarrow x_{0}\right) \text {. }$
我们指出<br/>
,定义中 $0<\left|x-x_{0}\right|$ 表示 $x \neq x_{0}$, 所以 $x \rightarrow x_{0}$ 吋 $f(x)$ 有没有极 限, 与 $f(x)$ 在点 $x_{1}$ 是否有定义并无关系.

### 函数极限的另一定义
定义 2<br/> 设函数 $f(x)$ 当 $|x|$ 大于某一正数时有定义. 如果存在常数 $A$, 对 于任意给定的正数 $\varepsilon$ (不论它多么小), 总存在豙正数 $X$, 使得当 $x$ 满足不等式 $|x|>X$ 时, 对应的函数值 $f(x)$ 都满足不等式$|f(x)-A|<\varepsilon$<br/>
那么常数 $A$ 就叫做<br/>
函数 $f(x)$ 当 $x \rightarrow \infty$ 时的极限, 
记作<br/>
$\lim _{x \rightarrow \infty} f(x)=A \text { 或 } f(x) \rightarrow A(\text { 当 } x \rightarrow \infty) \text {. }$

<!--定理 1 (函数极限的唯一性) 如果 $\lim _{x \rightarrow x_{10}} f(x)$ 存在, 那么这极限唯一.

定理 2(函数极限的局部有界性） 如果 $\lim _{x \rightarrow 1} f(x)=A$, 那么存在常数 $M>0$和 $\delta>0$, 使得当 $0<\left|x-x_{0}\right|<\delta$ 时,有 $|f(x)| \leqslant M$.


定理 3(函数极限的局部保号性) 如果 $\lim _{x \rightarrow x_{10}} f(x)=A$, 且 $A>0$ (或 $A<0$ ), 那么存在常数 $\delta>0$, 使得当 $0<\left|x-x_{11}\right|<\delta$ 时,有 $f(x)>0$ (或 $\left.f(x)<0\right)$.

定理 4 (函数极限与数列极限的关系) 如果极限 $\lim _{x \rightarrow x_{0}} f(x)$ 存在, $\left\{x_{n}\right\}$ 为 函数 $f(x)$ 的定义域内任一收敛于 $x_{0}$ 的数列, 且满足: $x_{n} \neq x_{0}\left(n \in \mathbf{N}^{+}\right)$, 那么相 应的函数值数列 $\left\{f\left(x_{n}\right)\right\}$ 必收敛,且 $\lim _{n \rightarrow \infty} f\left(x_{n}\right)=\lim _{x \rightarrow x_{0}} f(x)$.-->

### 无穷小的定义
定义 1<br/>
如果函数 $f(x)$ 当 $x \rightarrow x_{0}$ (或 $x \rightarrow \infty$ ) 时的极限为零, <br/>
那么称<br/>
函数 $f(x)$ 为当 $x \rightarrow x_{v}$ (或 $x \rightarrow \infty$ ) 时的无穷小.

### 无穷大的定义
定义 2<br/>
设函数 $f(x)$ 在 $x_{11}$ 的某一去心邻域内有定义 (或 $|x|$ 大于某一正 数时有定义). 如果对于任意给定的正数 $M$ (不论它多么大), 总存在正数 $\delta$ (或 正数 $X$ ), 只要 $x$ 适合不等式 $0<\left|x-x_{11}\right|<\delta$ (或 $|x|>X$ ), 对应的函数值 $f(x)$ 总满足不等式$|f(x)|>M$
则称<br/>
函数 $f(x)$ 为当 $x \rightarrow x_{10}$ (或 $x \rightarrow \infty$ ) 时的无穷大.
当 $x \rightarrow x_{0}$ (或 $x \rightarrow \infty$ ) 时的无穷大的函数 $f(x)$, 按函数极限定义来说,极限 是不存在的.<br/>
但为了便于叙述函数的这一性态, 我们也说<br/>
“函数的极限是无穷 大",<br/>
并记作<br/>
$\begin{array}{l}\lim _{x \rightarrow 2_{10}} f(x)=\infty \\\text { (或 } \lim _{x \rightarrow \infty} f(x)=\infty \text { ). }\end{array}$

### 无穷小的等级定义
定义:<br/>
如果 $\lim \frac{\beta}{\alpha}=0$, 就说 $\beta$ 是比 $\alpha$ 高阶的无穷小, <br/>
记作<br/>
$\beta=o(a)$;<br/>
如果 $\lim \frac{\beta}{\alpha}=\infty$,<br/>
就说<br/>
$\beta$ 是比 $\alpha$ 低阶的无穷小.<br/>
如果 $\lim \frac{\beta}{\alpha}=c \neq 0$, <br/>
就说<br/>
$\beta$ 与 $\alpha$ 是同阶无穷小;<br/>
如果 $\lim \frac{\beta}{\alpha^{k}}=c \neq 0, k>0$, <br/>
就说<br/>
$\beta$ 是关于 $\alpha$ 的 $\underline{\sim}$ 阶无穷小.<br/>
如果 $\lim \frac{\beta}{\alpha}=1$, <br/>
就说<br/>
$\beta$ 与 $\alpha$ 是等价无穷小, <br/>
记作<br/>
$\alpha \sim \beta$.<br/>

### 函数的连续定义
定义<br/> 
设函数 $y=f(x)$ 在点 $x_{0}$ 的某一邻域内有定义, 如果$\lim _{\Delta x \rightarrow 0} \Delta y=\lim _{\Delta x \rightarrow 0}\left[f\left(x_{11}+\Delta x\right)-f\left(x_{0}\right)\right]=0$<br/>
那么就称<br/>
函数 $y=f(x)$ 在点 $x_{0}$ 连续.<br/>

### 导数定义
定义<br/> 
设函数 $y=f(x)$ 在点 $x_{0}$ 的某个邻域内有定义, 当自变量 $x$ 在 $x_{0}$ 处 取得增量 $\Delta x$ (点 $x_{0}+\Delta x$ 仍在该邻域内) 时, 相应的函数取得增量 $\Delta y=f\left(x_{0}+\right.$ $\Delta x)-f\left(x_{0}\right)$; 如果 $\Delta y$ 与 $\Delta x$ 之比当 $\Delta x \rightarrow 0$ 时的极限存在,<br/>
则称<br/>
函数 $y=$ $f(x)$ 在喜 $x_{0}$ 处可导, 并称这个极限为函数 $y=f(x)$ 在点 $x_{0}$ 处的导数, <br/>
记为<br/>
$f^{\prime}\left(x_{0}\right)$, 即$f^{\prime}\left(x_{0}\right)=\lim _{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x}=\lim _{\Delta x \rightarrow 0} \frac{f\left(x_{0}+\Delta x\right)-f\left(x_{0}\right)}{\Delta x}$也可记作 $\left.y^{\prime}\right|_{x=x_{0}},\left.\frac{\mathrm{d} y}{\mathrm{~d} x}\right|_{x=x_{0}}$ 或 $\left.\frac{\mathrm{d} f(x)}{\mathrm{d} x}\right|_{x=x_{\mathrm{n}}}$.

### 可微定义
定义<br/>
设函数 $y=f(x)$ 在某区间内有定义, $x_{0}$ 及 $x_{0}+\Delta x$ 在这区间内, 如 果增量$\Delta y=f\left(x_{11}+\Delta x\right)-f\left(x_{0}\right)$
可表示为<br/>
$\Delta y=A \Delta x+o(\Delta x)$
其中<br/>
$A$ 是不依赖于 $\Delta x$ 的常数,<br/>
那么称<br/>
函数 $y=f(x)$ 在点 $x_{0}$ 是可微的, 而 $A \Delta x$ 叫做函数 $y=f(x)$ 在点 $x_{0}$ 相应于自变量增量 $\Delta x$ 的微分,<br/>
记作 $\mathrm{d} y$, 即
$\mathrm{d} y=A \Delta x .$

### 凹图
定义<br/>
设 $f(x)$ 在区间 $I$ 上连续,如果对 $I$ 上任意两点 $x_{1}, x_{2}$ 恒有$\text \quad f\left(\frac{x_{1}+x_{2}}{2}\right)<\frac{f\left(x_{1}\right)+f\left(x_{2}\right)}{2}$<br/>
那么称<br/>
$f(x)$ 在 $I$ 上的图形是 (向上)凹的 (或凹弧); 如果恒有$f\left(\frac{x_{1}+x_{2}}{2}\right)>\frac{f\left(x_{1}\right)+f\left(x_{2}\right)}{2}$
那么称<br/>
$f(x)$ 在 $I$ 上的图形是(向上)凸的(或凸弧).

### 函数极值定义
定义<br/>
设函数$f(x)$ 在点$x_{0}$ 的某邻域$U\left(x_{0}\right)$ 内有定义, 如果对于去心邻域$\stackrel{\circ}{U}\left(x_{0}\right)$ 内的任一$x$, 有$f(x)<f\left(x_{0}\right) \quad\left(\text { 或 } f(x)>f\left(x_{0}\right)\right),$
<br/>
那么就称<br/>
$f\left(x_{0}\right)$ 是函数 $f(x)$ 的一个极大值(或极小值).函数的极大值与极小值统称为函数的极值, 使函数取得极值的点称为极值点

### 原函数的定义
定义 1<br/>
如果在区间 $I$ 上, 可导函数 $F(x)$ 的导函数为 $f(x)$, 即对任一 $x \in I$, 都有$
F^{\prime}(x)=f(x) \text { 或 } \mathrm{d} F(x)=f(x) \mathrm{d} x \text {, }$<br/>
那么函数 $F(x)$ 就称为<br/>
$f(x)$ (或 $f(x) \mathrm{d} x)$ 在区间 $I$ 上的原函数.

### 不定积分的定义
定义 2<br/>
在区间 $I$ 上, 函数 $f(x)$ 的带有任意常数项的<br/>
原函数称为<br/> $f(x)$ （或 $f(x) \mathrm{d} x)$ 在区间 $I$ 上的不定积分, <br/>
记作<br/>
$\int f(x) \mathrm{d} x$<br/>
其中<br/>
记号 $\int$ 称为积分号, $f(x)$ 称为被积函数, $f(x) \mathrm{d} x$ 称为被积表达式, $x$ 称为 积分变壘.

### 定积分定义
定义<br/>
设函数 $f(x)$ 在 $[a, b]$ 上有界, 在 $[a, b]$ 中任意揷入若干个分点$a=x_{0}<x_{1}<x_{2}<\cdots<x_{n-1}<x_{n}=b$把区间 $[a, b]$ 分成 $n$ 个小区间$\left[x_{0}, x_{1}\right],\left[x_{1}, x_{2}\right], \cdots,\left[x_{n-1}, x_{n}\right]$各个小区间的长度依次为$\Delta x_{1}=x_{1}-x_{10}, \Delta x_{2}=x_{2}-x_{1}, \cdots, \Delta x_{n}=x_{n}-x_{n-1}$在每个小区间 $\left[x_{i-1}, x_{i}\right]$ 上任取一点 $\xi_{i} \quad\left(x_{i-1} \leqslant \xi_{i} \leqslant x_{i}\right)$, 作函数值 $f\left(\xi_{i}\right)$ 与小 区间长度 $\Delta x_{i}$ 的乘积 $f\left(\xi_{i}\right) \Delta x_{i} \quad(i=1,2, \cdots, n)$, 并作出和$S=\sum_{i=1}^{n} f\left(\xi_{i}\right) \Delta x_{i}$记 $\lambda=\max \left\{\Delta x_{1}, \Delta x_{2}, \cdots, \Delta x_{n}\right\}$, 如果不论对 $[a, b]$ 怎样划分, 也不论在小区 间 $\left[x_{i-i}, x_{i}\right]$ 上点 $\xi_{i}$ 怎样选取, 只要当 $\lambda \rightarrow 0$ 时, 和 $S$ 总趋于确定的极限 $I$,<br/>
那么 称<br/>
这个极限 $I$ 为函数 $f(x)$ 在区间 $[a, b]$ 上的定积分 (简 称 积 分 ), <br/>
记 作<br/>
$\int_{a}^{b} f(x) \mathrm{d} x$, 即$\int_{a}^{b} f(x) \mathrm{d} x=I=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}\right) \Delta x_{i}$<br/>
其中<br/>
$f(x)$ 叫做被积函数, $f(x) \mathrm{d} x$ 叫做被积表达式, $x$ 叫做积分变县, $a$ 叫做积 分下限, $b$ 叫做积分上限, $[a, b]$ 叫做积分区间.
利用 “ $\varepsilon-\delta$ ” 的说法, 上述定积分的定义可以表述如下:
设有常数 $I$, 如果对于任意给定的正数 $\varepsilon$, 总存在一个正数 $\delta$, 使得对于区间 $[a, b]$ 的任何分法, 不论 $\xi_{i}$ 在 $\left[x_{i-1}, x_{i}\right]$ 中怎样选取, 只要 $\lambda<\delta$, 总有$\left|\sum_{i=1}^{n} f\left(\xi_{i}\right) \Delta x_{i}-I\right|<\varepsilon$成立, 则称 $I$ 是 $f(x)$ 在区间 $[a, b]$ 上的定和分, 记作 $\int_{a}^{b} f(x) \mathrm{d} x$.

### 反常积分定义
定义 1<br/>
设函数 $f(x)$ 在区间 $[a,+\infty)$ 上连续, 取 $t>a$, 如果极限
$\lim _{n+\infty} \int_{a}^{t} f(x) \mathrm{d} x$存在,
则称<br/>
此极限为函数 $f(x)$ 在无穷区间 $[a,+\infty)$ 上的反常积分, <br/>
记作<br/>
$\int_{a}^{+\infty} f(x) \mathrm{d} x$, 即
$\int_{a}^{+\infty} f(x) \mathrm{d} x=\lim _{1 \rightarrow+\infty} \int_{a}^{t} f(x) \mathrm{d} x$
这时也称反常积分 $\int_{a}^{+\infty} f(x) \mathrm{d} x$ 收敛; 如果上述极限不存在, 则函数 $f(x)$ 在无穷 区间 $[a,+\infty)$ 上的反常积分 $\int_{a}^{+\infty} f(x) \mathrm{d} x$ 就没有意义, 习惯上称为友常积分 $\int_{a}^{+\infty} f(x) \mathrm{d} x$ 发散, 这时记号 $\int_{a}^{+\infty} f(x) \mathrm{d} x$ 不再表示数值了.
类似地, 设函数 $f(x)$ 在区间 $(-\infty, b]$ 上连续, 取 $t<b$. 如果极限$\lim _{t \rightarrow-\infty} \int_{t}^{b} f(x) \mathrm{d} x$存在, 则称此极限为函数 $f(x)$ 在无穷区间 $(-\infty, b]$ 上的反常积分, 记作 $\int_{-\infty}^{b} f(x) \mathrm{d} x$, 即$\int_{-\infty}^{b} f(x) \mathrm{d} x=\lim _{1 \rightarrow-\infty} \int_{t}^{b} f(x) \mathrm{d} x$
这时也称反常积分 $\int_{-\infty}^{b} f(x) \mathrm{d} x$ 收鉄; 如果上述极限不存在, 则称反常积分 $\int_{-\infty}^{b} f(x) \mathrm{d} x$ 发散.设函数 $f(x)$ 在区间 $(-\infty,+\infty)$ 上连续, 如果反常积分$\int_{-\infty}^{0} f(x) \mathrm{d} x \text { 和 } \int_{0}^{+\infty} f(x) \mathrm{d} x$都收敛, 则称上述两反常积分之和为函数 $f(x)$ 在无穷区间 $(-\infty,+\infty)$ 上的反 常积分, 记作 $\int_{-\infty}^{+\infty} f(x) \mathrm{d} x$, 即$
\begin{aligned}\int_{-\infty}^{+\infty} f(x) \mathrm{d} x &=\int_{-\infty}^{0} f(x) \mathrm{d} x+\int_{0}^{+\infty} f(x) \mathrm{d} x \\&=\lim _{r \rightarrow-\infty} \int_{i}^{0} f(x) \mathrm{d} x+\lim _{i \rightarrow+\infty} \int_{0}^{\prime} f(x) \mathrm{d} x\end{aligned}$<br/><br/>
这时也称<br/>
反常积分 $\int_{-\infty}^{+\infty} f(x) \mathrm{d} x$ 收敛; 否则就称反常积分 $\int_{-\infty}^{+\infty} f(x) \mathrm{d} x$ 发散. 上述反常积分统称为无穷限的反常积分.

### 极限存在的定义
定义 2<br/>
设函数 $f(x)$ 在 $(a, b]$ 上连续,点 $a$ 为 $f(x)$ 的㻓点. 取 $t>a$, 如果 极限$\lim _{x \rightarrow a^{a}} \int_{1}^{b} f(x) \mathrm{d} x$存在, 则称<br/>
此极限为函数 $f(x)$ 在 $(a, b]$ 上的反常积分,<br/> 
仍然记作<br/>
$\int_{a}^{b} f(x) \mathrm{d} x$, 即$\int_{a}^{b} f(x) \mathrm{d} x=\lim _{1 . . .^{+}} \int_{1}^{h} f(x) \mathrm{d} x$
这时也称 反常积分 $\int_{a}^{b} f(x) \mathrm{d} x$ 收玫. 如果上述极限不存在, 则称 反常积分 $\int_{a}^{b} f(x) \mathrm{d} x$ 发散.
类似地, 设函数 $f(x)$ 在 $[a, b)$ 上连续, 点 $b$ 为 $f(x)$ 的瑯点. 取 $t<b$, 如果 极限$\lim _{1 \rightarrow h^{-}} \int_{a}^{t} f(x) \mathrm{d} x$存在, 则定义$\int_{a}^{b} f(x) \mathrm{d} x=\lim _{1 \rightarrow h^{-}} \int_{a}^{t} f(x) \mathrm{d} x$
否则,就称反常积分 $\int_{a}^{b} f(x) \mathrm{d} x$ 发散.
设函数 $f(x)$ 在 $[a, b]$ 上除点 $c(a<c<b)$ 外连续, 点 $c$ 为 $f(x)$ 的㻓点. 如 果两个反常积分$
\int_{a}^{x} f(x) \mathrm{d} x \text { 与 } \int_{r}^{b} f(x) \mathrm{d} x$
都收敛, 则定义$\begin{aligned}\int_{a}^{a} f(x) \mathrm{d} x &=\int_{a}^{r} f(x) \mathrm{d} x+\int_{c}^{b} f(x) \mathrm{d} x \\&=\lim _{1 \rightarrow c^{-}} \int_{a}^{t} f(x) \mathrm{d} x+\lim _{t \rightarrow c^{+}} \int_{1}^{b} f(x) \mathrm{d} x\end{aligned}$否则, 就称反常积分 $\int_{a}^{h} f(x) \mathrm{d} x$ 发散.

### 函数定义域定义
定义 1 <br/>
设 $D$ 是 $\mathbf{R}^{2}$ 的一个非空子集, <br/>
称映射 $f: D \rightarrow \mathbf{R}$ 为定义在 $D$ 上的二 元函数, <br/>
通常记为<br/>
$z=f(x, y),(x, y) \in $或$z=f(P), P \in D$其中点集 $D$ 称为该函数的定义域, $x 、 y$ 称为自变量, $z$ 称为因变量

### 二重极限定义
定义 2<br/>
设二元函数 $f(P)=f(x, y)$ 的定义域为 $D, P_{0}\left(x_{0}, y_{0}\right)$ 是 $D$ 的聚 点. 如果存在常数 $A$, 对于任意给定的正数 $\varepsilon$, 总存在正数 $\delta$, 使得当点 $P(x, y)$ $\in D \cap U^{\circ}\left(P_{0}, \delta\right)$ 时, 都有$|f(P)-A|=|f(x, y)-A|<\varepsilon$成立, <br/>
那么就称<br/>
常数 $A$ 为函数 $f(x, y)$ 当 $(x, y) \rightarrow\left(x_{0}, y_{0}\right)$ 时的极限, <br/>
记作 <br/>
$\lim _{(x, y) \rightarrow\left(x_{0}, y_{0}\right)} f(x, y)=A \quad$ 或 $\quad f(x, y) \rightarrow A\left((x, y) \rightarrow\left(x_{0}, y_{0}\right)\right)$, 也记作$\lim _{P \rightarrow P_{0}} f(P)=A \quad \text { 或 } \quad f(P) \rightarrow A\left(P \rightarrow P_{0}\right) .$为了区别于一元函数的极限, 我们把二元函数的极限叫做二重极限.

### 二重极限的定义
定义 3<br/>
设二元函数 $f(P)=f(x, y)$ 的定义域为 $D, P_{0}\left(x_{0}, y_{0}\right)$ 为 $D$ 的聚 点,且 $P_{0} \in D$. 如果
$\lim _{(x, y) \rightarrow\left(x_{0}, y_{0}\right)} f(x, y)=f\left(x_{0}, y_{0}\right)$
则称<br/>
函数 $f(x, y)$ 在点 $P_{0}\left(x_{0}, y_{0}\right)$ 连续.
设函数 $f(x, y)$ 在 $D$ 上有定义, $D$ 内的每一点都是函数定义域的聚点. 如 果函数 $f(x, y)$ 在 $D$ 的每一点都连续, 那么就称函数 $f(x, y)$ 在 $D$ 上连续,或者 称 $f(x, y)$ 是 $D$ 上的连续函数.

### 间断点定义
定义 4<br/>
设函数 $f(x, y)$ 的定义域为 $D, P_{0}\left(x_{0}, y_{0}\right)$ 是 $D$ 的聚点. 如果函数 $f(x, y)$ 在点 $P_{0}\left(x_{0}, y_{0}\right)$ 不连续,<br/>
则称<br/>
$P_{0}\left(x_{0}, y_{0}\right)$ 为函数 $f(x, y)$ 的间断点.

### 偏导数定义
定义<br/>
设函数 $z=f(x, y)$ 在点 $\left(x_{0}, y_{0}\right)$ 的某一邻域内有定义, 当 $y$ 固定在 $y_{0}$ 而 $x$ 在 $x_{0}$ 处有增韋 $\Delta x$ 时, 相应的函数有增量$f\left(x_{0}+\Delta x, y_{0}\right)-f\left(x_{0}, y_{0}\right)$如果$\lim _{\Delta x \rightarrow 0} \frac{f\left(x_{0}+\Delta x, y_{0}\right)-f\left(x_{0}, y_{0}\right)}{\Delta x}$存在, <br/>
则称<br/>
此极限为函数 $z=f(x, y)$ 在点 $\left(x_{0}, y_{0}\right)$ 处对 $x$ 的偏导数, <br/>
记作<br/>
$\left.\frac{\partial z}{\partial x}\right|_{x=x_{0} \atop y=y_{0}},\left.\frac{\partial f}{\partial x}\right|_{x=x_{0} \atop y=y_{0}},\left.z_{x}\right|_{x=x_{0} \atop y=y_{0}}$ 或 $f_{x}\left(x_{0}, y_{0}\right)$. (1)

### 全微分定义
定义 <br/>
设函数 $z=f(x, y)$ 在点 $(x, y)$ 的某邻域内有定义, 如果函数在点 $(x, y)$ 的全增量$\Delta z=f(x+\Delta x, y+\Delta y)-f(x, y)$可表示为$\Delta z=A \Delta x+B \Delta y+o(\rho)$其中 $A 、 B$ 不依赖于 $\Delta x 、 \Delta y$ 而仅与 $x 、 y$ 有关, $\rho=\sqrt{(\Delta x)^{2}+(\Delta y)^{2}}$, <br/>
则称<br/>
函数 $z=f(x, y)$ 在点 $(x, y)$ 可微分, 而 $A \Delta x+B \Delta y$ 称为函数 $z=f(x, y)$ 在点 $(x, y)$ 的全微分, <br/>
记作<br/>
$\mathrm{d} z$, 即$\mathrm{d} z=A \Delta x+B \Delta y$如果函数在区域 $D$ 内各点处都可微分, 那么称这函数在 $D$ 内可微分.

### 一元向量值函数
定义<br/>
设数集 $D \subset \mathbf{R}$,<br/>
则称<br/>
映射 $f: D \rightarrow \mathbf{R}^{n}$ 为一元向量值函数, <br/>
通常记为<br/>
$\boldsymbol{r}=\boldsymbol{f}(t), t \in D$其中数集 $D$ 称为函数的定义域, $t$ 称为自变量, $r$ 称为因变量.

### 向量值函数极限定义
定义 1<br/>
设向量值函数 $\boldsymbol{f}(t)$ 在点 $t_{0}$ 的某一去心邻域内有定义, 如果存在一 个常向刯 $r_{0}$, 对于任意给定的正数 $\varepsilon$, 总存在正数 $\delta$, 使得当 $t$ 满足 $0<\left|t-t_{0}\right|$ $<\delta$ 时, 对应的函数值 $\boldsymbol{f}(t)$ 都满足不等式$\left|\boldsymbol{f}(t)-\boldsymbol{r}_{0}\right|<\varepsilon$
那么, 常向量$r_{0}$ 就叫做<br/>
向量值函数 $f(t)$ 当 $t \rightarrow t_{0}$ 时的极限, <br/>
记作<br/>
$\lim _{t \rightarrow t_{0}} f(t)=r_{0} \text { 或 } f(t) \rightarrow r_{0}, t \rightarrow t_{0} \text {. }$
容易证明: 向量值函数 $\boldsymbol{f}(t)$ 当 $t \rightarrow t_{0}$ 时的极限存在的充分必要条件是: $f(t)$ 的三个分量函数 $f_{1}(t), f_{2}(t), f_{3}(t)$ 当 $t \rightarrow t_{0}$ 时的极限都存在; 在函数 $f(t)$ 当 $t \rightarrow t_{0}$ 时的极限存在时, 其极限$\lim _{t \rightarrow t_{0}} f(t)=\left(\lim _{t \rightarrow t_{0}} f_{1}(t), \lim _{t \rightarrow t_{0}} f_{2}(t), \lim _{t \rightarrow t_{0}} f_{3}(t)\right)$设向量值函数 $\boldsymbol{f}(t)$ 在点 $t_{0}$ 的某一邻域内有定义, 若$\lim _{t \rightarrow t_{\mathrm{a}}} \boldsymbol{f}(t)=\boldsymbol{f}\left(t_{0}\right)$则称向量值函数 $\boldsymbol{f}(t)$ 在 $t_{0}$ 连续.

### 向量值函数导数定义
定义 2<br/>
设向量值函数 $\boldsymbol{r}=\boldsymbol{f}(t)$ 在点 $t_{0}$ 的某一邻域内有定义, 如果$\lim _{\Delta t \rightarrow 0} \frac{\Delta r}{\Delta t}=\lim _{\Delta t-0} \frac{f\left(t_{0}+\Delta t\right)-f\left(t_{0}\right)}{\Delta t}$存在, <br/>
那么就称<br/>
这个极限向基为向量值函数 $r=f(t)$ 在 $t_{0}$ 处的导数或导向量,<br/>
记作<br/>
$\boldsymbol{f}^{\prime}\left(t_{0}\right)$ 或 $\left.\frac{\mathrm{d}}{\mathrm{d} t}\right|_{t=t_{0}}$.

### 向量值函数极值定义
定义<br/>
设函数 $z=f(x, y)$ 的定义域为 $D, P_{0}\left(x_{0}, y_{0}\right)$ 为 $D$ 的内点. 若存在 $P_{0}$ 的某个邻域 $U\left(P_{0}\right) \subset D$, 使得对于该邻域内异于 $P_{0}$ 的任何点 $(x, y)$, 都有$f(x, y)<f\left(x_{0}, y_{0}\right)$<br/>
则称<br/>
函数 $f(x, y)$ 在点 $\left(x_{0}, y_{0}\right)$ 有极大值 $f\left(x_{0}, y_{0}\right)$, 点 $\left(x_{0}, y_{0}\right)$ 称为函数 $f(x, y)$ 的极大值点; 若对于该邻域内异于 $P_{0}$ 的任何点 $(x, y)$, 都有$f(x, y)>f\left(x_{0}, y_{0}\right)$
则称函数 $f(x, y)$ 在点 $\left(x_{0}, y_{0}\right)$ 有极小值 $f\left(x_{0}, y_{0}\right)$, 点 $\left(x_{0}, y_{0}\right)$ 称为函数 $f(x, y)$ 的极小值点. 极大值、极小值统称为极值. 便得函数取得衱值的点称为极 值点.

### 二重积分定义
定义<br/>
设 $f(x, y)$ 是有界闭区域 $D$ 上的有界函数. 将闭区域 $D$ 任意分成 $n$ 个小闭区域$\Delta \sigma_{1}, \Delta \sigma_{2}, \cdots, \Delta \sigma_{n}$其中 $\Delta \sigma_{i}$ 裏示第 $i$ 个小闭区域, 也表示它的面积. 在每个 $\Delta \sigma_{i}$ 上壬取一点 $\left(\xi_{i}, \eta_{i}\right)$, 作乘积 $f\left(\xi_{i}, \eta_{i}\right) \Delta \sigma_{i}(i=1,2, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right) \Delta \sigma_{i}$. 如果当 各小闭区域的直径中的最大值 $\lambda$ 趋于蕶时, 这和的极限总存在, <br/>
则称<br/>
此极限为 函数 $f(x, y)$ 在闭区域 $D$ 上的二重积分, <br/>
记作 <br/>
$\iint_{D} f(x, y) \mathrm{d} \sigma$, 即
$\iint_{D} f(x, y) \mathrm{d} \sigma=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right) \Delta \sigma_{i}$<br/>
其中<br/>
$f(x, y)$ 叫做被积函数, $f(x, y) \mathrm{d} \sigma$ 叫做被积表达式, $\mathrm{d} \sigma$ 叫做面积元素, $x$ 与 $y$ 叫做积分变量, $D$ 叫做积分区域, $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right) \Delta \sigma_{i}$ 叫做积分和.

### 三重积分定义
定义<br/>
设 $f(x, y, z)$ 是空间有界闭区域 $\Omega$ 上的有界函数. 将 $\Omega$ 任意分成 $n$ 个小闭区域$\Delta v_{1}, \Delta v_{2}, \cdots, \Delta v_{n}$
其中 $\Delta v_{i}$ 表示第 $i$ 个小闭区域，也表示它的体积. 在每个 $\Delta v_{i}$ 上任 取一点 $\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)$, 作乘积 $f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta v_{i} \quad(i=1,2, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta v_{i}$. 如果当各小闭区域直径中的最大值 $\lambda$ 趋于零时这和的极限总存在,<br/>
则称<br/>
此极限 为函数 $f(x, y, z)$ 在闭区域 $\Omega$ 上的三重积分. <br/>
记作<br/>
$\iiint_{\Omega} f(x, y, z) \mathrm{d} v$, 即
$\iint_{\Omega} f(x, y, z) \mathrm{d} v=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta v_{i}$<br/>
其中<br/>
$\mathrm{d} v$ 叫做体积元素.

### 第一类曲线积分定义
定义<br/>
设 $L$ 为 $x O y$ 面内的一条光滑曲线弧, 函数 $f(x, y)$ 在 $L$ 上有界. 在 $L$ 上任意揷入一点列 $M_{1}, M_{2}, \cdots, M_{n-1}$ 把 $L$ 分成 $n$ 个小段. 设第 $i$ 个小段的长 度为 $\Delta s_{i}$. 又 $\left(\xi_{i}, \eta_{i}\right)$ 为第 $i$ 个小段上任意取定的一点,作乘积 $f\left(\xi_{i}, \eta_{i}\right) \Delta s_{i}(i=$ $1,2, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right) \Delta s_{i}$, 如果当各小弧段的长度的最大值 $\lambda \rightarrow 0$ 时, 这和的极限总存在, <br/>
则称<br/>
此极限为函数 $f(x, y)$ 在曲线弧 $L$ 上对弧长的曲线 积分或第一类曲线积分, <br/>
记作<br/>
$\int_{L} f(x, y) \mathrm{d} s$, 即$\int_{L} f(x, y) \mathrm{d} s=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right) \Delta s_{i}$
其中<br/>
$f(x, y)$ 叫做被积函数, L: 叫做积分弧段.

### 第二次曲线积分定义
定义<br/>
设 $L$ 为 $x O y$ 面内从点 $A$ 到点 $B$ 的一条有向光滑曲线弧, 函数 $P(x, y), Q(x, y)$ 在 $L$ 上有界. 在 $L$ 上沿 $L$ 的方向任意揷入一点列 $M_{1}\left(x_{1}\right.$, $\left.y_{1}\right), M_{2}\left(x_{2}, y_{2}\right), \cdots, M_{n-1}\left(x_{n-1}, y_{n-1}\right)$, 把 $L$ 分成 $n$ 个有向小弧段$\widehat{M_{i-1} M_{i}} \quad\left(i=1,2, \cdots, n ; M_{0}=A, M_{n}=B\right)$设 $\Delta x_{i}=x_{i}-x_{i-1}, \Delta y_{i}=y_{i}-y_{i-1}$, 点 $\left(\xi_{i}, \eta_{i}\right)$ 为 $\widehat{M_{i-1} M_{i}}$ 上任意取定的点. 如果 当各小弧段长度的最大值 $\lambda \rightarrow 0$ 时, $\sum_{i=1}^{n} P\left(\xi_{i}, \eta_{i}\right) \Delta x_{i}$ 的极限总存在, <br/>
则称<br/>
此极 限为函数 $P(x, y)$ 在有向曲线弧 $L$ 上对坐标 $x$ 的曲线积分,<br/>
记作<br/>
$\int_{L} P(x, y) \mathrm{d} x$.类似地, 如果 $\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} Q\left(\xi_{i}, \eta_{i}\right) \Delta y_{i}$ 总存在, <br/>
则称<br/>
此极限为函数 $Q(x, y)$ 在有向 曲线弧 $L$ 上对坐标 $y$ 的曲线积分, <br/>
记作<br/>
$\int_{L} Q(x, y) \mathrm{d} y$. 即$\begin{array}{l}\int_{L} P(x, y) \mathrm{d} x=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} P\left(\xi_{i}, \eta_{i}\right) \Delta x_{i} \\\int_{L} Q(x, y) \mathrm{d} y=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} Q\left(\xi_{i}, \eta_{i}\right) \Delta y_{i}\end{array}$
其中<br/>
$P(x, y) 、 Q(x, y)$ 叫做被积函数, $L$ 叫做积分弧段. 以上两个积分也称为第二类曲线积分.

### 第一类曲面积分
定义<br/>
设曲面 $\Sigma$ 是光滑的 (1, 函数 $f(x, y, z)$ 在 $\Sigma$ 上有界. 把 $\Sigma$ 任意分成 $n$ 小块 $\Delta S_{i}\left(\Delta S_{i}\right.$ 同时也代表第 $i$ 小块曲面的面积 $)$,设 $\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)$ 是 $\Delta S_{i}$ 上任意 取定的一点,作乘积 $f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}(i=1,2,3, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i},\right.$, $\left.\zeta_{i}\right) \Delta S_{i}$, 如果当各小块曲面的直径的最大值 $\lambda \rightarrow 0$ 时, 这和的极限总存在, <br/>
则称<br/>
此极限为函数 $f(x, y, z)$ 在曲面 $\Sigma$ 上对面积的曲面积分或第一类曲面积分,<br/>
记 作<br/>
$\iint_{\Sigma} f(x, y, z) \mathrm{d} S$, 即$\iint_{\Sigma} f(x, y, z) \mathrm{d} S=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}$

### 第二次曲线积分极限定义
定义<br/>
设 $L$ 为 $x O y$ 面内从点 $A$ 到点 $B$ 的一条有向光滑曲线弧, 函数 $P(x, y) 、 Q(x, y)$ 在 $L$ 上有界. 在 $L$ 上沿 $L$ 的方向任意揷入一点列 $M_{1}\left(x_{1}\right.$, $\left.y_{1}\right), M_{2}\left(x_{2}, y_{2}\right), \cdots, M_{n-1}\left(x_{n-1}, y_{n-1}\right)$, 把 $L$ 分成 $n$ 个有向小弧段$\widehat{M_{i-1} M_{i}} \quad\left(i=1,2, \cdots, n ; M_{0}=A, M_{n}=B\right)$设 $\Delta x_{i}=x_{i}-x_{i-1}, \Delta y_{i}=y_{i}-y_{i-1}$, 点 $\left(\xi_{i}, \eta_{i}\right)$ 为 $\widehat{M_{i-1} M_{i}}$ 上任意取定的点. 如果 当各小弧段长度的最大值 $\lambda \rightarrow 0$ 时, $\sum_{i=1}^{n} P\left(\xi_{i}, \eta_{i}\right) \Delta x_{i}$ 的极限总存在, <br/>
则称<br/>
此极 限为函数 $P(x, y)$ 在有向曲线弧 $L$ 上对坐标 $x$ 的曲线积分,<br/>
记作<br/>
$\int_{L} P(x, y) \mathrm{d} x$. 类似地, 如果 $\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} Q\left(\xi_{i}, \eta_{i}\right) \Delta y_{i}$ 总存在, 则称此极限为函数 $Q(x, y)$ 在有向 曲线弧 $L$ 上对坐标 $y$ 的曲线积分, 记作 $\int_{L} Q(x, y) \mathrm{d} y$. 即$\begin{array}{l}\int_{L} P(x, y) \mathrm{d} x=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} P\left(\xi_{i}, \eta_{i}\right) \Delta x_{i} \\\int_{L} Q(x, y) \mathrm{d} y=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} Q\left(\xi_{i}, \eta_{i}\right) \Delta y_{i}\end{array}$
其中<br/>
$P(x, y) 、 Q(x, y)$ 叫做被积函数, $L$ 叫做积分弧段. 以上两个积分也称为第二类曲线积分.

### 第一类曲面积分定义
定义<br/>
设曲面 $\Sigma$ 是光滑的 (3, 函数 $f(x, y, z)$ 在 $\Sigma$ 上有界. 把 $\Sigma$ 任意分成 $n$ 小块 $\Delta S_{i}\left(\Delta S_{i}\right.$ 同时也代表第 $i$ 小块曲面的面积 $)$,设 $\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)$ 是 $\Delta S_{i}$ 上任意 取定的一点,作乘积 $f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}(i=1,2,3, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right.$, $\left.\zeta_{i}\right) \Delta S_{i}$, 如果当各小块曲面的直径的最大值 $\lambda \rightarrow 0$ 时, 这和的极限总存在,<br/>
则称<br/>
此象限为函数 $f(x, y, z)$ 在曲面 $\Sigma$ 上对面积的曲面积分或第一类曲面积分,<br/>
记 作<br/>
$\iint_{\Sigma} f(x, y, z) \mathrm{d} S$, 即$\iint_{\Sigma} f(x, y, z) \mathrm{d} S=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}$<br/>
其中<br/>
$f(x, y, z)$ 叫做被积函数, $\Sigma$ 叫做积分曲面.我们指出, 当 $f(x, y, z)$ 在光滑曲面 $\Sigma$ 上连续时, 对面积的曲面积分是存 在的. 今后总假定 $f(x, y, z)$ 在 $\Sigma$ 上连续.

### 曲面积分
定义<br/>
设 $\Sigma$ 为光滑的有向曲面, 函数 $R(x, y, z)$ 在 $\Sigma$ 上有界. 把 $\Sigma$ 任意分 成 $n$ 块小曲面 $\Delta S_{i}\left(\Delta S_{i}\right.$ 同时又表示第 $i$ 块小曲面的面积 $), \Delta S_{i}$ 在 $x O y$ 面上的 投影为 $\left(\Delta S_{i}\right)_{x y},\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)$ 是 $\Delta S_{i}$ 上任意取定的一点. 如果当各小块曲面的直 径的最大值 $\lambda \rightarrow 0$ 时,$\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} R\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)\left(\Delta S_{i}\right)_{x y}$
<!--定义 设曲面 $\Sigma$ 是光滑的 (1), 函数 $f(x, y, z)$ 在 $\Sigma$ 上有界. 把 $\Sigma$ 任意分成 $n$ 小块 $\Delta S_{i}\left(\Delta S_{i}\right.$ 同时也代表第 $i$ 小块曲面的面积 $)$, 设 $\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)$ 是 $\Delta S_{i}$ 上任意
取定的一点,作乘积 $f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}(i=1,2,3, \cdots, n)$, 并作和 $\sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}\right.$,
$\left.\zeta_{i}\right) \Delta S_{i}$, 如果当各小块曲面的直径的最大值 $\lambda \rightarrow 0$ 时, 这和的极限总存在, 则称 此极限为函数 $f(x, y, z)$ 在曲面 $\Sigma$ 上对面积的曲面积分或第一类曲面积分, 记 作 $\iint_{\Sigma} f(x, y, z) \mathrm{d} S$, 即
$$
\iint_{\Sigma} f(x, y, z) \mathrm{d} S=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} f\left(\xi_{i}, \eta_{i}, \zeta_{i}\right) \Delta S_{i}
$$-->
总存在,<br/>
则称<br/>
此极限为函数 $R(x, y, z)$ 在有向曲面 $\Sigma$ 上对坐标 $x, y$ 的曲面积 分,<br/>
记作<br/>
$\iint_{\Sigma} R(x, y, z) \mathrm{d} x \mathrm{~d} y$, 即$\iint_{\Sigma} R(x, y, z) \mathrm{d} x \mathrm{~d} y=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} R\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)\left(\Delta S_{i}\right)_{x y}$<br/>
其中<br/>
$R(x, y, z)$ 叫做被积函数, $\Sigma$ 叫做积分曲面.类似地可以定义函数 $P(x, y, z)$ 在有向曲面 $\Sigma$ 上对坐标 $y, z$ 的曲面积分 $\iint_{\Sigma} P(x, y, z) \mathrm{d} y \mathrm{~d} z$ 及函数 $Q(x, y, z)$ 在有向曲面 $\Sigma$ 上对坐标 $z_{、} x$ 的曲面积分 $\iint_{\Sigma} Q(x, y, z) \mathrm{d} z \mathrm{~d} x$ 分别为$\begin{array}{l}\iint_{\Sigma} P(x, y, z) \mathrm{d} y \mathrm{~d} z=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} P\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)\left(\Delta S_{i}\right)_{y z} \\\iint_{\Sigma} Q(x, y, z) \mathrm{d} z \mathrm{~d} x=\lim _{\lambda \rightarrow 0} \sum_{i=1}^{n} Q\left(\xi_{i}, \eta_{i}, \zeta_{i}\right)\left(\Delta S_{i}\right)_{z x}\end{array}$
以上三个曲面积分也称为第二类曲面积分.

### 无穷级数定义
定义<br/>
如果级数 $\sum_{n=1}^{\infty} u_{n}$ 的部分和数列 $\left\{s_{n}\right\}$ 有极限 $s$, 即$\lim _{n \rightarrow \infty} s_{n}=s,$<br/>
则称<br/>
无穷级数 $\sum_{n=1}^{\infty} u_{n}$ 收玫, 这时极限 $s$ 叫做这级数的和, 并写成$s=u_{1}+u_{2}+\cdots+u_{n}+\cdots$如果 $\left\{s_{n} \mid\right.$ 没有极限, 则称无穷级数 $\sum_{n=1}^{\infty} u_{n}$ 发散.显然, 当级数收玫时, 其部分和 $s_{n}$ 是级数的和 $s$ 的近似值, 它们之间的差值$r_{n}=s-s_{n}=u_{n+1}+u_{n+2}+\cdots$<br/>
叫做<br/>
级数的余项. 用近似值 $s_{n}$ 代替和 $s$ 所产生的误差是这个余项的绝对值, 即 误差是 $\left|r_{n}\right|$.

### 函数项级数定义
定义<br/>
设有函数项级数 $\sum_{n=1}^{\infty} u_{x}(x)$. 如果对于任意给定的正数 $\varepsilon$, 都存在善 一个只依赖于 $\varepsilon$ 的正整数 $N$, 使得当 $n>N$ 时, 对区间 $I$ 上的一切 $x$, 都有不等 式$\left|r_{n}(x)\right|=\left|s(x)-s_{n}(x)\right|<\varepsilon$成立,<br/>
则称<br/>
函数项级数 $\sum_{n=1}^{\infty} u_{n}(x)$ 在区间 $I$ 上二致收敛于和 $s(x)$, 也称函数序 列 $\left\{s_{n}(x)\right\}$ 在区间 $I$ 上一致收敛于 $s(x)$.
