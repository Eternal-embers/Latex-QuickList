# Latex 公式速查

- [Latex 公式速查](#latex-公式速查)
  - [函数](#函数)
    - [对数与指数](#对数与指数)
    - [三角函数](#三角函数)
    - [其他函数](#其他函数)
  - [符号](#符号)
    - [运算符](#运算符)
    - [集合](#集合)
    - [关系符号](#关系符号)
    - [几何符号](#几何符号)
    - [逻辑符号](#逻辑符号)
    - [箭头 - `arrow`](#箭头---arrow)
  - [希腊字母](#希腊字母)
  - [字体](#字体)
    - [黑板报粗体](#黑板报粗体)
    - [粗体](#粗体)
    - [斜体](#斜体)
    - [无衬线体](#无衬线体)
    - [手写体](#手写体)
    - [注释文本](#注释文本)
  - [颜色](#颜色)
  - [空格](#空格)
  - [上下标与积分等](#上下标与积分等)
  - [分式](#分式)
  - [矩阵](#矩阵)
    - [无框矩阵 - `matrix`](#无框矩阵---matrix)
    - [行列式 - `vmatrix`](#行列式---vmatrix)
    - [范数矩阵 - `Vmatrix`](#范数矩阵---vmatrix)
    - [小括号矩阵 - `pmatrix`](#小括号矩阵---pmatrix)
    - [大括号矩阵 - `Bmatrix`](#大括号矩阵---bmatrix)
    - [方括号矩阵 - `bmatrix`](#方括号矩阵---bmatrix)
    - [边框 - `boxed{}`](#边框---boxed)
  - [数组 - `array`](#数组---array)
    - [定界符](#定界符)
      - [竖线](#竖线)
      - [小括号](#小括号)
      - [大括号](#大括号)
      - [方括号](#方括号)
    - [分割线](#分割线)
      - [实竖线](#实竖线)
      - [虚竖线](#虚竖线)
      - [实横线 - `\hline`](#实横线---hline)
      - [虚横线 - `\hdashline`](#虚横线---hdashline)
      - [应用 - 分块矩阵](#应用---分块矩阵)
      - [应用 - 制作表格](#应用---制作表格)
  - [条件表达式，方程式](#条件表达式方程式)
    - [条件表达式 - `cases`](#条件表达式---cases)
    - [编号的方程式 - `equation`](#编号的方程式---equation)
    - [多公式有编号 - `align`](#多公式有编号---align)
    - [多公式无编号 - `align*`](#多公式无编号---align)
      - [多公式无编号](#多公式无编号)
      - [单方程式多行写](#单方程式多行写)
    - [自定义对齐方式](#自定义对齐方式)
    - [方程组](#方程组)

> 本文仅提供的能够在 $Markdown$ 中使用的 $Latex$ 公式。

如何插入 $Latex$ 公式？

- 行内公式：`$公式$`
- 独立公式：`$$公式$$`

## 函数

### 对数与指数

$a^x$  `a^x`  
$\sqrt{x}$ `\sqrt{x}`  
$\sqrt[3]{x}$ `\sqrt[3]{x}`  
$\sqrt[a]{x}$ `\sqrt[a]{x}`  
$\exp x$ `\exp x`  
$\log x$ `\log x`  
$\lg x$ `\lg x`  
$\ln x$ `\ln x`

### 三角函数

$\sin x$ `\sin x`  
$\cos x$ `\cos x`  
$\tan x$ `\tan x`  
$\cot x$ `\cot x`  
$\sec x$  `\sec x`  
$\csc x$  `\csc x`  
$\arcsin x$ `\arcsin x`  
$\arccos x$  `\arccos x`  
$\arctan x$  `\arctan x`  
$\sinh x$ `\sinh x`  
$\cosh x$ `\cosh x`  
$\tanh x$ `\tanh x`  

### 其他函数

最小值： $\min x$ `\min x`
最大值： $\max x$ `\max x`  
最大公约数： $\gcd x$ `\gcd x`  
角度： $\deg$ `\deg`  
极限： $\lim_{x \to \infty}f(x)$ `\lim_{x \to \infty}f(x)`  
上确界： $\sup M$ `\sup M`  
下确界： $\inf M$ `\inf M`  
行列式： $\det A$ `\det A`  
维数： $\dim A$ `\dim A`  
矩阵kernel： $\ker A$ `\ker A`  
投影： $\Pr$ `\Pr`  
同调群：$\hom$ `\hom`  
复数的幅角： $\arg z$ `\arg z`  
向下取整： $\lfloor x \rfloor$ `\lfloor x \rfloor`  
向上取整： $\lceil x \rceil$ `\lceil x \rceil`  
自定义函数： $\operatorname{function} x$ `\operatorname{function} x`  

## 符号

### 运算符

$\pm$ `\pm`  
$\mp$ `\mp`  
$\dotplus$ `\dotplus`  
$\times$ `\times`  
$\div$ `\div`  
$\frac{a}{b}$ `\frac{a}{b}`  
$\divideontimes$ `\divideontimes`  
$\backslash$ `\backslash`  
$\cdot$ `\cdot`  
$\ast$ `\ast`  
$\circ$ `\circ`  
$\bullet$ `\bullet`  
$\boxplus$ `\boxplus`  
$\boxminus$ `\boxminus`  
$\boxtimes$ `\boxtimes`  
$\boxdot$ `\boxdot`  
$\oplus$  `\oplus`  
$\ominus$ `\ominus`  
$\otimes$  `\otimes`  
$\oslash$  `\oslash`  
$\odot$ `\odot`  
$\bigoplus$ `bigoplus`  
$\bigotimes$ `\bigotimes`  
$\bigodot$ `\bigodot`  

### 集合

$\{ \}$ `\{ \}`  
$\empty$ `\empty`  
$\varnothing$ `\varnothing`  
$\in$ `\in`  
$\not\in$ `\notin` 或 `\not\in`  
$\ni$ `\ni`  
$\notni$ `\notni` 或 `\not\ni`  
$\cap$ `\cap`  
$\Cap$ `\Cap`  
$\sqcap$ `\sqcap`  
$\bigcap$ `\bigcap`  
$\cup$ `\cup`  
$\Cup$ `\Cup`  
$\sqcup$ `\sqcup`  
$\bigcup$  `\bigcup`  
$\bigsqcup$ `\bigscup`  
$\uplus$ `\uplus`  
$\biguplus$  `\biguplus`  
$\subset$  `\subset`  
$\Subset$  `\Subset`  
$\sqsubset$ `\sqsubset`  
$\supset$ `\supset`  
$\Supset$ `\Supset`  
$\sqsupset$ `\sqsupset`  
$\subseteq$ `\subseteq`  
$\nsubseteq$ `\nsubseteq`  
$\subsetneq$ `\subsetneq`  
$\varsubsetneq$ `\varsubsetneq`  
$\sqsubseteq$ `\sqsubseteq`  
$\supseteq$ `\supseteq`  
$\nsupseteq$ `\nsupseteq`  
$\supsetneq$ `\supsetneq`  
$\varsupsetneq$ `\varsupsetneq`  
$\sqsupseteq$ `\sqsupseteq`  
$\sqsupset$ `\sqsupset`  
$\subseteqq$ `\subseteqq`  
$\nsubseteqq$ `\nsubseteqq`  
$\subsetneqq$ `\subsetneqq`  
$\varsubsetneqq$ `\varsubsetneqq`  
$\supseteqq$ `\supseteqq`  
$\nsupseteqq$ `\nsupseteqq`  
$\supsetneqq$ `\supsetneqq`  
$\varsupsetneqq$ `\varsupsetneqq`  

### 关系符号

$\ne$ `\ne` 或 `\neq`  
$\equiv$ `\equiv`  
$\not\equiv$ `\not\equiv`  
$\doteq$ `\doteq`  
$\doteqdot$ `\doteqdot`  
$\sim$ `\sim`  
$\nsim$ `\nsim`  
$\backsim$ `\backsim`  
$\thicksim$ `\thicksim`  
$\simeq$  `\simeq`  
$\backsimeq$ `\backsimeq`  
$\eqsim$ `\eqsim`  
$\cong$ `\cong`  
$\ncong$ `\ncong`  
$\approx$ `\approx`  
$\thickapprox$ `\thickapprox`  
$\approxeq$ `\approxeq`  
$\asymp$ `\asymp`  
$\propto$ `\propto`  
$\varpropto$ `\varpropto`  
$\ngtr$ `\ngtr`  
$\gg$ `\gg`  
$\ggg$ `\ggg`  
$\not\ggg$ `\not\ggg`  
$\gtrdot$ `\gtrdot`  
$\ngtr$ `\ngtr`  
$\lneq$ `\lneq`  
$\leqq$ `\leqq`  
$\nleq$ `\nleq`  
$\nleqq$ `\nleqq`  
$\lneqq$ `\lneqq`  
$\lvertneqq$ `\lvertneqq`  
$\ge$ `\ge`  
$\geq$ `\geq`  
$\gneq$ `\gneq`  
$\geqq$ `\geqq`  
$\ngeq$ `\ngeq`  
$\ngeqq$ `\ngeqq`  
$\gneqq$ `\gneqq`  
$\gvertneqq$ `\gvertneqq`  

### 几何符号

$\parallel$ `\parallel`  
$\nparallel$ `\nparallel`  
$\shortparallel$ `\shortparallel`  
$\nshortparallel$ `nshortparallel`  
$\perp$ `\perp`  
$\angle$ `\angle`  
$\sphericalangle$ `\sphericalangle`  
$\measuredangle$ `\measuredangle`  
$45^\circ$ `45^\circ`  
$\Box$ `\Box`  
$\blacksquare$ `\blacksquare`  
$\diamond$ `\diamond`  
$\Diamond$ `\Diamond`  
$\lozenge$ `\lozenge`  
$\blacklozenge$ `\blacklozenge`  
$\bigstar$ `\bigstar`  
$\bigcirc$ `\bigcirc`  
$\triangle$ `\triangle`  
$\bigtriangleup$ `\bigtriangleup`  
$\bigtriangledown$ `\bigtriangledown`  
$\vartriangle$ `\vartriangle`  
$\triangledown$ `\triangledown`  
$\blacktriangle$ `\blacktriangle`  
$\blacktriangledown$ `\blacktriangledown`  
$\blacktriangleleft$ `\blacktriangleleft`  
$\blacktriangleright$ `\blacktriangleright`  

### 逻辑符号

$\forall$ `\forall`  
$\exists$ `\exists`  
$\nexists$ `\nexists`  
$\therefore$ `\therefore`  
$\because$ `\because`  
$\And$ `\And`  
$\mid$ `\mid`  
$\lor$ `\lor` 或 `\vee`  
$\land$ `\land` 或 `\wedge`  
$\bar{q}$ `\bar{q}`  
$\overline{q}$ `\overline{q}`  
$\lnot$ `\lnot` 或 `\neg`  
$\bot$ `\bot`  
$\top$ `\top`  
$\vdash$ `\vdash`  
$\dashv$ `\dashv`  
$\vDash$ `\vDash`  
$\Vdash$ `\Vdash`  
$\models$ `\models`  
$\ulcorner$ `\ulcorner`  
$\urcorner$ `\urcorner`  
$\llcorner$ `\llcorner`  
$\lrcorner$ `\lrcorner`

### 箭头 - `arrow`

$\rightarrow$ `\rightarrow`  
$\nrightarrow$ `\nrightarrow`  
$\longrightarrow$ `\longrightarrow`  
$\Rightarrow$ `\Rightarrow`  
$\nRightarrow$ `\nRightarrow`  
$\Longrightarrow$ `\Longrightarrow`  
$\leftarrow$ `\leftarrow`  
$\nleftarrow$ `n\leftarrow`  
$\longleftarrow$ `\longleftarrow`  
$\Leftarrow$ `\Leftarrow`  
$\nLeftarrow$ `\nLeftarrow`  
$\Longleftarrow$ `\Longleftarrow`  
$\leftrightarrow$ `\leftrightarrow`  
$\nleftrightarrow$ `\nleftrightarrow`  
$\Leftrightarrow$ `\Leftrightarrow`  
$\nLeftrightarrow$ `\nLeftrightarrow`  
$\longleftrightarrow$ `\longleftrightarrow`  
$\iff$ `iff`  
$\Longleftrightarrow$ `\Longleftrightarrow`  
$\uparrow$  `\uparrow`  
$\downarrow$ `\downarrow`  
$\updownarrow$ `\updownarrow`  
$\Uparrow$ `\Uparrow`  
$\Downarrow$ `\Downarrow`  
$\nearrow$ `\nearrow`  
$\swarrow$ `\swarrow`  
$\nwarrow$ `\nwarrow`  
$\searrow$ `\searrow`  
$\rightharpoonup$ `\rightharpoonup`  
$\rightharpoondown$ `\rightharpoondown`  
$\leftharpoonup$ `\leftharpoonup`  
$\leftharpoondown$ `\leftharpoondown`  
$\upharpoonleft$ `\upharpoonleft`  
$\downharpoonleft$ `\downharpoonleft`  
$\upharpoonright$ `\upharpoonright`  
$\downharpoonright$ `\downharpoonright`  
$\rightleftharpoons$ `\rightleftharpoons`  
$\leftrightharpoons$ `\leftrightharpoons`  
$\curvearrowleft$ `\curvearrowleft`  
$\curvearrowright$ `\curvearrowright`  
$\circlearrowleft$ `\circlearrowleft`  
$\circlearrowright$ `\circlearrowright`  
$\Lsh$ `\Lsh`  
$\Rsh$ `\Rsh`  
$\upuparrows$ `\upuparrows`  
$\downdownarrows$ `\downdownarrows`  
$\leftleftarrows$ `\leftleftarrows`  
$\rightrightarrows$ `\rightrightarrows`  
$\stackrel{text}{\longrightarrow}$ `\stackrel{text}{\longrightarrow}`  
$\stackrel{text}{\longleftarrow}$ `\stackrel{text}{\longleftarrow}`  
$\stackrel{text}{\downarrow}$ `\stackrel{text}{\downarrow}`  
$\stackrel{text}{\uparrow}$ `\stackrel{text}{\uparrow}`  

## 希腊字母

$\alpha$ `\alpha`  
$\beta$ `\beta`  
$\gamma$ `\gamma`  
$\delta$ `\delta`  
$\epsilon$ `\epsilon`  
$\varepsilon$ `\varepsilon`  
$\zeta$ `\zeta`  
$\eta$ `\eta`  
$\theta$ `\theta`  
$\vartheta$ `\vartheta`  
$\iota$ `\iota`  
$\kappa$ `\kappa`  
$\lambda$ `\lambda`  
$\mu$ `\mu`  
$\nu$ `\nu`  
$\xi$ `\xi`  
$\pi$ `\pi`  
$\varpi$ `\varpi`  
$\rho$ `\rho`  
$\varrho$ `\varrho`  
$\sigma$ `\sigma`  
$\varsigma$ `\varsigma`  
$\tau$ `\tau`  
$\upsilon$ `\upsilon`  
$\phi$ `\phi`  
$\varphi$ `\varphi`  
$\chi$ `\chi`  
$\psi$ `\psi`  
$\omega$ `\omega`  
$\Gamma$ `\Gamma`  
$\Delta$ `\Delta`  
$\Theta$ `\Theta`  
$\Lambda$ `\Lambda`  
$\Xi$ `\Xi`  
$\Pi$ `\Pi`  
$\Sigma$ `\Sigma`  
$\Upsilon$ `\Upsilon`  
$\Phi$ `\Phi`  
$\Psi$ `\Psi`  
$\Omega$ `\Omega`  

## 字体

### 黑板报粗体

> 只对大写字母有效

$\mathbb{FONT}$ `\mathbb{FONT}`

### 粗体

> 对大小写字母、希腊字母都有效

$\mathbf{FONT}$ `\mathbf{FONT}`  
$\mathbf{font}$ `\mathbf{font}`  
$\mathbf{\digamma\Theta\Nu\Tau}$ `\mathbf{\digamma\Theta\Nu\Tau}`  

### 斜体

$\mathit{1234567890}$ `\mathit{1234567890}`  
$\mathit{abcdefg}$ `\mathit{abcdefg}`  
$\mathit{ABCDEFG}$ `\mathit{ABCDEFG}`  

### 无衬线体

$\mathsf{ABCDEFG}$ `\mathsf{ABCDEFG}`

### 手写体

$\mathcal{ABCDEFG}$ `\mathcal{ABCDEFG}`

### 注释文本

用 `text{}` 在公式中添加文本： $\text{注释信息}$ `\text{注释信息}`

## 颜色

格式：

```latex
\color{颜色}{文本}
```

旧版浏览器支持：

$\color{gray}{text}$ `\color{gray}{text}`  
$\color{silver}{text}$ `\color{silver}{text}`  
$\color{blue}{text}$ `\color{blue}{text}`  
$\color{yellow}{text}$ `\color{yellow}{text}`  
$\color{red}{text}$ `\color{red}{text}`  
$\color{lime}{text}$ `\color{lime}{text}`  
$\color{green}{text}$ `\color{green}{text}`  
$\color{fuchsia}{text}$ `\color{fuchsia}{text}`  

较新浏览器支持 `\color{#rgb}{text}` 来自定义更多的颜色，`#rgb` 的 `r、g、b` 分别可以是十六进制表示的 `0~255` 的数。

$\color{#ffdddd}{text}$ `\color{#ffdddd}{text}`  
$\color{#ff8888}{text}$ `\color{#ff8888}{text}`  
$\color{#ffaa11}{text}$ `\color{#ffaa11}{text}`  
$\color{#ffccaa}{text}$ `\color{#ffccaa}{text}`  
$\color{#ffdd66}{text}$ `\color{#ffdd66}{text}`  
$\color{#ffbbee}{text}$ `\color{#ffbbee}{text}`  
$\color{#aaaaff}{text}$ `\color{#aaaaff}{text}`  
$\color{#7777ff}{text}$ `\color{#7777ff}{text}`  
$\color{#66ccff}{text}$ `\color{#66ccff}{text}`  
$\color{#99ccff}{text}$ `\color{#99ccff}{text}`  
$\color{#00eeff}{text}$ `\color{#00eeff}{text}`  
$\color{#bbffee}{text}$ `\color{#bbffee}{text}`  
$\color{#99ff99}{text}$ `\color{#99ff99}{text}`  
$\color{#44bb66}{text}$ `\color{#44bb66}{text}`  
$\color{#44ff77}{text}$ `\color{#44ff77}{text}`  
$\color{#0088ff}{text}$ `\color{#0088ff}{text}`  
$\color{#22cc88}{text}$ `\color{#22cc88}{text}`  
$\color{#777777}{text}$ `\color{#777777}{text}`  
$\color{#aaaaaa}{text}$ `\color{#aaaaaa}{text}`  
$\color{#f0f0f0}{text}$ `\color{#f0f0f0}{text}`  

## 空格

- `\,` 表示一个窄空格，$\frac{1}{6}$ M 的宽度
- `\` 或 `\:` 表示一个中等空格
- `\;` 表示一个大空格
- `\quad` 表示一个字母 M 宽度的空格
- `\qquad` 表示两个 \quad 的宽度
- `\!` 表示一个负的窄空格，缩进$\frac{1}{6}M$ 的宽度
- `\\` 表示换行

$$
\boxed{
\begin{array}{c|c}
窄空格 & a\,b \\ \hline
中等空格 & a\: b \\ \hline
大空格 & a\;b \\ \hline
字母M的宽度 & a\quad b \\ \hline
两个M的宽度 & a\qquad b \\ \hline
负窄空格 & a\!b
\end{array}\\
}
$$

## 上下标与积分等

$x^2$ `x^2`  

$x^{a + b}$ `x^{a+b}`  

$a_1$ `a_1`  

$a_{ij}$ `a_{ij}`  

前置上下标： ${}_1^2\!X_3^4$ `{}_1^2\!x_3^4`  

正上方标记：$\sum\limits^n$ `\sum\limits^n`  

正下方标记：$\min\limits_{i \leq k \leq j - 1}$ `\min\limits_{i \leq k \leq j - 1}`  

导数： $x^\prime$ `x^\prime`  或 `x'`  

导数点： $\dot{x}$ `\dot{x}`  

向量：$\vec{x}$ `\vec{x}`  

左长箭头： $\overleftarrow{a + b}$ `\overleftarrow{a + b}`  

右长箭头： $\overrightarrow{a + b}$ `\overrightarrow{a + b}`  

$\widehat{abc}$ `\widehate{abc}`  

上弧： $\overset{\frown}{AB}$ `\overset{\frown}{AB}`  

上划线： $\overline{abc}$ `\overline{abc}`  

下划线： $\underline{abc}$ `\underline{abc}`  

上括号： $\overbrace{1 + 2 + \cdots + 100}$ `\overbrace{1 + 2 + \cdots + 100}`  

上括号示例： $\begin{matrix}5050\\\overbrace{1 + 2 + \cdots + 100}\end{matrix}$ `\begin{matrix}5050\\\overbrace{1 + 2 + \cdots + 100}\end{matrix}`  

下括号： $\underbrace{1 + 2 + \cdots + 100}$ `\underbrace{1 + 2 + \cdots + 100}`  

下括号示例： $\begin{matrix}\underbrace{1 + 2 + \cdots + 100}\\5050\end{matrix}$ `\begin{matrix}\underbrace{1 + 2 + \cdots + 100}\\5050\end{matrix}`  

求和： $\sum_{k = 1}^{\infty} f(x)$ `\sum_{k = 1}^{\infty} f(x)`  

求和： $\Sigma_{x = 1}^{\infty} f(x)$ `\Sigma_{x = 1}^{t = \infty} f(x)`  

求积： $\prod_{i = 1}^{n} x_i$ `\prod_{i = 1}^{n} x_i`  

上积： $\coprod_{i = 1}^{n} x_i$ `\coprod_{i = 1}^{n} x_i`  

极限： $\lim_{x\to\infty} f(x)$ `\lim_{x\to\infty} f(x)`  

积分： $\int_{a}^{b} f(x)dx$ `\int_{a}^{b} f(x)dx`  

双重积分： $\iint_{a}^{b} f(x) \, dx \, dy$ `\iint_{a}^{b} f(x) \, dx \, dy`  

三重积分： $\iiint_a^{b} f(x) \, dx \, dy \, dz$ `\iiint_a^{b} f(x) \, dx \, dy \, dz`  

闭合的曲线、曲面积分： $\oint_{C} x^2 \, dx+ y \, dy$ `\oint_{C} x^2 \, dx+ y \, dy`  

## 分式

分数：
$\frac{a + b}{c + d}$ `\frac{a + b}{c + d}`  
$\frac{dx}{dy}$ `\frac{dx}{dy}`

连分式： $\cfrac{1}{2 + \cfrac{3}{4 + \cfrac{5}{6 + \cdots}}}$ `\cfrac{1}{2 + \cfrac{3}{4 + \cfrac{5}{6 + \cdots}}}`  

$\cfrac{a_1}{b1 + \cfrac{a_2}{b_2 + \cfrac{a_3}{b_3 + \cdots}}}$ `\cfrac{a_1}{b1 + \cfrac{a_2}{b_2 + \cfrac{a_3}{b_3 + \cdots}}}`  

二项式系数： $C_n^r = \dbinom{n}{r}$ `C_n^r = \dbinom{n}{r}`

## 矩阵

语法：

```latex
\begin{类型}
公式
\end{类型}
```

矩阵中 `&` 分隔元素，`\\` 进行换行
横三点： $\cdots$ `\cdots`  
竖三点： $\vdots$ `\vdots`  
斜三点： $\ddots$ `\ddots`  

### 无框矩阵 - `matrix`

$$
\begin{matrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{matrix}\\
$$

```latex
\begin{matrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{matrix}
```

### 行列式 - `vmatrix`

$$
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{21} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}\\
$$

```latex
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{21} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
```

### 范数矩阵 - `Vmatrix`

$$
\begin{Vmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,1} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n,1} & a_{n,2} & \cdots & a_{n,n}
\end{Vmatrix}\\
$$

```latex
\begin{Vmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,1} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n,1} & a_{n,2} & \cdots & a_{n,n}
\end{Vmatrix}
```

### 小括号矩阵 - `pmatrix`

$$
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}\\
$$

```latex
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}
```

### 大括号矩阵 - `Bmatrix`

$$
\begin{Bmatrix}
a_{11} & a_{12} & a_{13} & a_{14} \\
a_{21} & a_{22} & a_{23} & a_{24} \\
a_{31} & a_{32} & a_{33} & a_{34} \\
a_{41} & a_{42} & a_{43} & a_{44}  
\end{Bmatrix}\\
$$

```latex
\begin{Bmatrix}
a_{11} & a_{12} & a_{13} & a_{14} \\
a_{21} & a_{22} & a_{23} & a_{24} \\
a_{31} & a_{32} & a_{33} & a_{34} \\
a_{41} & a_{42} & a_{43} & a_{44}  
\end{Bmatrix}
```

### 方括号矩阵 - `bmatrix`

$$
\begin{bmatrix}
a_{11} & a_{12} & a_{13} & \cdots & a_{1n} \\
a_{21} & a_{22} & a_{23} & \cdots & a_{2n} \\
a_{31} & a_{32} & a_{33} & \cdots & a_{3n} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & a_{n3} & \cdots & a_{nn}
\end{bmatrix}\\
$$

```latex
\begin{bmatrix}
a_{11} & a_{12} & a_{13} & \cdots & a_{1n} \\
a_{21} & a_{22} & a_{23} & \cdots & a_{2n} \\
a_{31} & a_{32} & a_{33} & \cdots & a_{3n} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & a_{n3} & \cdots & a_{nn} 
\end{bmatrix}
```

### 边框 - `boxed{}`

$$
\begin{bmatrix}
\boxed{-1} & 3 & 0 & 2 \\
0 & \boxed{1} & 3 & 1 \\
0 & 0 & 0 & \boxed{2} \\
0 & 0 & 0 & 0
\end{bmatrix}\\
$$

```latex
\begin{bmatrix}
\boxed{-1} & 3 & 0 & 2 \\
0 & \boxed{1} & 3 & 1 \\
0 & 0 & 0 & \boxed{2} \\
0 & 0 & 0 & 0
\end{bmatrix}\\
```

## 数组 - `array`

$$
\begin{array}{}
a & b \\
c & d  
\end{array}\\
$$

```latex
\begin{array}{}
a & b \\
c & d  
\end{array}
```

### 定界符

语法：

```latex
\left 符号
公式
\right 符号
```

#### 竖线

$$
\left |
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right | \\
$$

```latex
\left |
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right | 
```

#### 小括号

$$
\left (
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right ) \\
$$

```latex
\left (
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right )
```

#### 大括号

$$
\left \{
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right \}\\
$$

```latex
\left \{
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right \}
```

> 注：`{}` 为特殊字符，无法直接使用，应使用 `\{` 和 `\}` 来输出

#### 方括号

$$
\left [
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{}
a_{11} & a_{12} \\
a_{13} & a_{14} \\
\end{array}
\right ]
```

### 分割线

#### 实竖线

$$
\left [
\begin{array}{c|c|c|c|c}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15}\\
a_{21} & a_{22} & a_{23} & a_{24} & a_{25}\\
a_{31} & a_{32} & a_{33} & a_{34} & a_{35}\\
a_{41} & a_{42} & a_{43} & a_{44} & a_{45}\\
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{c|c|c|c|c}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15}\\
a_{21} & a_{22} & a_{23} & a_{24} & a_{25}\\
a_{31} & a_{32} & a_{33} & a_{34} & a_{35}\\
a_{41} & a_{42} & a_{43} & a_{44} & a_{45}\\
a_{51} & a_{52} & a_{53} & a_{54} & a_{55} 
\end{array}\\
\right ]
```

#### 虚竖线

$$
\left [
\begin{array}{c:c:c:c:c}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{c:c:c:c:c}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]\\
```

#### 实横线 - `\hline`

$$
\left [
\begin{array}{}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
\hline
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
\hline
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
\hline
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
\hline
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
\hline
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
\hline
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
\hline
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
\hline
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]
```

#### 虚横线 - `\hdashline`

$$
\left [
\begin{array}{}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
\hdashline
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
\hdashline
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
\hdashline
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
\hdashline
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{}
a_{11} & a_{12} & a_{13} & a_{14} & a_{15} \\
\hdashline
a_{21} & a_{22} & a_{23} & a_{24} & a_{25} \\
\hdashline
a_{31} & a_{32} & a_{33} & a_{34} & a_{35} \\
\hdashline
a_{41} & a_{42} & a_{43} & a_{44} & a_{45} \\
\hdashline
a_{51} & a_{52} & a_{53} & a_{54} & a_{55}
\end{array}
\right ]
```

#### 应用 - 分块矩阵

$$
\left [
\begin{array}{cc:cc}
1 & 0 & 1 & -2 \\
0 & 1 & 0 & 1 \\
\hdashline
-1 & 2 & -1 & 0 \\
0 & -1 & 0 & -1
\end{array}
\right ]\\
$$

```latex
\left [
\begin{array}{cc:cc}
1 & 0 & 1 & -2 \\
0 & 1 & 0 & 1 \\
\hdashline
-1 & 2 & -1 & 0 \\
0 & -1 & 0 & -1
\end{array}
\right ]
```

#### 应用 - 制作表格

$$
\boxed{
    \begin{array}{c|c}
    矩阵类型 & 关键字 \\ \hline
    |A| & vmatrix \\ \hline
    \parallel & Vmatrix \\ \hline
    () & pmatrix \\ \hline
    \{\} & Bmatrix \\ \hline
    [\ ] & bmatrix
    \end{array}
}\\
$$

```latex
\boxed{
    \begin{array}{c|c}
    矩阵类型 & 关键字 \\ \hline
    |A| & vmatrix \\ \hline
    \parallel & Vmatrix \\ \hline
    () & pmatrix \\ \hline
    \{\} & Bmatrix \\ \hline
    [\ ] & bmatrix
    \end{array}
}
```

## 条件表达式，方程式

### 条件表达式 - `cases`

$$
f(x) =
\begin{cases}
\begin{aligned}
\frac{\sin x}{|x|},x \ne 0 \\
1,x = 0\\
\end{aligned}
\end{cases}\\
$$

```latex
f(x) =
\begin{cases}
\begin{aligned}
\frac{\sin x}{|x|},x \ne 0 \\
1,x = 0\\
\end{aligned}
\end{cases}
```

### 编号的方程式 - `equation`

$$
\begin{equation}
z = (a+b)^4= a^4 + 4a^3b + 6a^2b^2 + 4ab^3 + b^4.
\end{equation}\\
$$

```latex
\begin{equation}
z = (a+b)^4= a^4 + 4a^3b + 6a^2b^2 + 4ab^3 + b^4.
\end{equation}
```

### 多公式有编号 - `align`

$$
\begin{align}
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
 \nabla \cdot \mathbf{B} &= 0 \\
 \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
 \nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0\varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
 \end{align}\\
$$

```latex
\begin{align} 
\nabla \cdot \mathbf{E} &= \frac{\rho}{\varepsilon_0} \\
 \nabla \cdot \mathbf{B} &= 0 \\
 \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
 \nabla \times \mathbf{B} &= \mu_0 \mathbf{J} + \mu_0\varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}
 \end{align}
```

### 多公式无编号 - `align*`

#### 多公式无编号

$$
\begin{align*}
E = mc^2 \\
e^{i\pi} + 1 = 0
\end{align*}\\
$$

```latex
\begin{align*}
E = mc^2 \\
e^{i\pi} + 1 = 0
\end{align*}
```

#### 单方程式多行写

$$
\begin{align*}
   z & = (a+b)^4 \\
     & = (a+b)^2(a+b)^2 \\
     & = (a^2+2ab+b^2)(a^2+2ab+b^2) \\
     & = a^4 + 4a^3b + 6a^2b^2 + 4ab^3 + b^4
 \end{align*}\\
$$

```latex
\begin{align*}
   z & = (a+b)^4 \\
     & = (a+b)^2(a+b)^2 \\
     & = (a^2+2ab+b^2)(a^2+2ab+b^2) \\
     & = a^4 + 4a^3b + 6a^2b^2 + 4ab^3 + b^4
 \end{align*}
```

$$
\begin{align*}
& a_1 \wedge a_2 \wedge \cdots \wedge (a_i \wedge x) \wedge a_{i + 1} \wedge \cdots \wedge a_n\\
& = (a_1 \wedge a_2 \wedge \cdots \wedge a_i \wedge a_{i + 1} \wedge \cdots \wedge a_n) \wedge x\\
& = x \wedge x\\
& = 0
\end{align*}
$$

```latex
\begin{align*}
& a_1 \wedge a_2 \wedge \cdots \wedge (a_i \wedge x) \wedge a_{i + 1} \wedge \cdots \wedge a_n\\
& = (a_1 \wedge a_2 \wedge \cdots \wedge a_i \wedge a_{i + 1} \wedge \cdots \wedge a_n) \wedge x\\
& = x \wedge x\\
& = 0
\end{align*}
```

### 自定义对齐方式

在 `align` 或 `align*` 环境下，在公式左侧添加 `&` 可以使得公式左对齐，否则默认为居中对齐。
实际上将 `&` 的作用是为公式设置一个对齐点，多个公式的对齐点会在同一竖线上。  

- 将标记的 $=$ 和 $+$ 之间保持对齐

$$
\begin{align*}
\phi(N) &= N - \frac{N}{p_1} - \frac{N}{p_2} \cdots - \frac{N}{p_k}\\
& +\frac{N}{p_1p_2} + \frac{N}{p_1p_3} + \cdots\\
& +\frac{N}{p_1p_2p_3} - \frac{N}{p_2p_2p_4} \cdots\\
& +\cdots \\
& = N \times \frac{p_1 - 1}{p_1} \times \frac{p_2 - 1}{p_2}\cdots \times \frac{p_m - 1}{p_m}
\end{align*}
$$

```latex
\begin{align*}
\phi(N) &= N - \frac{N}{p_1} - \frac{N}{p_2} \cdots - \frac{N}{p_k}\\
& +\frac{N}{p_1p_2} + \frac{N}{p_1p_3} + \cdots\\
& +\frac{N}{p_1p_2p_3} - \frac{N}{p_2p_2p_4} \cdots\\
& +\cdots \\
& = N \times \frac{p_1 - 1}{p_1} \times \frac{p_2 - 1}{p_2}\cdots \times \frac{p_m - 1}{p_m}
\end{align*}
```

- 将 $\cdots$ 之间保持对齐

$$
\begin{align*}
\phi(N) = N - \frac{N}{p_1} - \frac{N}{p_2} &\cdots - \frac{N}{p_k}\\
+\frac{N}{p_1p_2} + \frac{N}{p_1p_3} + &\cdots\\
+\frac{N}{p_1p_2p_3} - \frac{N}{p_2p_2p_4} &\cdots\\
+&\cdots \\
= N \times \frac{p_1 - 1}{p_1} \times \frac{p_2 - 1}{p_2} &\cdots \times \frac{p_m - 1}{p_m}
\end{align*}
$$

### 方程组

$$
\begin{cases}
x + y - z = 0 \\
2x - y + z = 2 \\
x + y + 2z = 4
\end{cases}\\
$$

```latex
\begin{cases}
x + y - z = 0 \\
2x - y + z = 2 \\
x + y + 2z = 4
\end{cases}
```

或者

```latex
\left\{ \begin{aligned}
x + y - z = 0 \\
2x - y + z = 2 \\
x + y + 2z = 4
\end{aligned} \right.
```

> `\left\{ 公式 \right.` 实现只有左边出现界定符大括号 `{`  
> `\begin{aligned} 公式 \end{aligned}` 实现公式右对齐  
