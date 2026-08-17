---
title: Second Day of High School
Description: nothing
published: 2026-08-06
date: 2026-08-06
draft: false
tags: ["Study", "Senior High"]
category: "School"
pinned: false
auther: Sharkerl
location: 32.08, 118.76
---

### 不等式(常用变形)

$\sum_{i=1}^n a_{i} \geq n \sqrt[n]{a_1 a_2 \cdots a_n}$ <br><br>
$a_1 a_2 \cdots a_n \leq \left(\dfrac{\sum_{i=1}^n a_{i}}{n}\right)^n$ <br><br>
$\left(\sum_{i = 1}^n a_i\right)\left(\sum_{i = 1}^n b_i\right) \geq \left(\sum_{i = 1}^n \sqrt{a_i b_i}\right)^2$ $a_i, b_i > 0$ <br><br>
$\sum_{i = 1}^n \dfrac{b_i ^2}{a_i} \geq \dfrac{(\sum_{i = 1}^n b_i)^2}{\sum_{i = 1}^n a_i}$ <br><br>

### 均值不等式中的待定系数法

`e.g.` 求函数$y = (x+2)(x+5)(3-x)$的最大值, 其中$x \in (0,3)$.

  **错误:** 变形成 $\rightarrow$ $\frac{1}{2}(x + 2)(x + 5)(6 - 2x)$  <br>
  实际上发现每项无法取到相等的值. <br>

  **待定系数法凑系数** 
  我们需要凑出可以让没项都相等的系数.
  设 $y = \frac{1}{ab}(ax + 2a)(bx + 5b)(3 - x)$, 取到最大值时
  $ax + 2a = bx + 5b = 3 - x$, 解得$x = \frac{3 - 2a}{a + 1} = \frac{3 - 5b}{b + 1}$, 我们只要解
$$
\begin{equation*}
\begin{cases}
a + b = 1 \\
\\
\dfrac{3 - 2a}{a + 1} = \dfrac{3 - 5b}{b + 1} \\
\end{cases}
\end{equation*}
$$
求出 
$$
\begin{equation*}
\begin{cases}
a = \frac{2}{3} \\
b = \frac{1}{3} \\
\end{cases}
\end{equation*}
$$
因此$y = \frac{9}{2}(\frac{2}{3}x + \frac{4}{3})(\frac{1}{3}x + \frac{5}{3})(3 - x) \leq 36$, $x = 1 \iff y_{\max} = 36$

### 均值不等式中的补项

`e.g.` 设 $x, y, z \in \mathbb{R}^+$, 且 $xyz = 1$, 求证 $\dfrac{x^n}{(1+y)(1+z)} + \dfrac{y^n}{(1+z)(1+x)} + \dfrac{z^n}{(1+x)(1+y)} \geq \dfrac{3}{4}$.<br><br>

若原式 = $\frac{3}{4}$, 则 $x = y = z = 1$, 凑项从而使用均值不等式, 注意到分母有两项, 或许可以:<br>

$\dfrac{x^n}{(1+y)(1+z)} + \frac{1 + y}{8} + \frac{1 + z}{8}$, 需要每项都为 $\frac{1}{4}$, 因此补项需要除以 8, 我们想在使用
不等式后去根号, 分母也是 4, 因此还需要补上 (n - 3) 个 $\frac{1}{4}$, $\dfrac{x^n}{(1+y)(1+z)} + \dfrac{1 + y}{8} + \dfrac{1 + z}{8}$
$+ \underbrace{\frac{1}{4} + \cdots +\frac{1}{4}}_{(n-3)个} \geq \dfrac{nx}{4}$ <br>
同理 $\cdots$ <br>
接着三式相加: <br>
$\dfrac{x^n}{(1+y)(1+z)} + \dfrac{y^n}{(1+z)(1+x)} + \dfrac{z^n}{(1+x)(1+y)} + \dfrac{x + y + z}{4} + (n - 2)\dfrac{3}{4} \geq \dfrac{n}{4}(x + y + z) \leq \dfrac{n}{4} 3 \sqrt[3]{xyz} = \dfrac{3n}{4}$ <br>

移项后即可证明.

### 均值不等式中分式的分子分母次数不一致问题

`e.g.1`已知 $a > 0, b > 0, c > 0, abc = 1$, 求证 $\dfrac{1}{a^3(b + c)} + \dfrac{1}{b^3(c + a)} + \dfrac{1}{c^3(a + b)} \geq \dfrac{3}{2}$ <br><br>
观察到分子为 0 次, 分母为 4 次, 我们想让分子与分母**同次**, 或者分子为分母的**平方倍次**, 因此可以符合柯西不等式的常用变形, 显然, 我们可以将
原式变形为 $\dfrac{a^2 b^2 c^2}{a^3(b + c)} + \dfrac{a^2 b^2 c^2}{b^3(c + a)} + \dfrac{a^2 b^2 c^2}{c^3(a + b)} = \dfrac{bc}{a(b + c)} + \dfrac{ac}{b(c + a)} + \dfrac{ab}{c(a + b)}$ <br>
$\Rightarrow \dfrac{b^2 c^2}{a(b + c)} + \dfrac{a^2 c^2}{b(c + a)} + \dfrac{a^2 b^2}{c(a + b)}$ <br>
明显现在分子是 4 次, 分母是 2 次<br>
$\Rightarrow$ 左 $\geq \dfrac{(bc + ac + ab)^2}{2(ab + bc + ac)} = \dfrac{ab + bc + ac}{2} \geq \dfrac{3 \sqrt[3]{a^2 b^2 c^2}}{2} = \dfrac{3}{2}$ <br><br>
`e.g.2`
