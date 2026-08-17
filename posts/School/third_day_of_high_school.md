---
title: Third Day of High School
Description: nothing
published: 2026-08-07
date: 2026-08-07
draft: false
tags: ["Study", "Senior High"]
category: "School"
pinned: false
auther: Sharkerl
location: 32.08, 118.76
---

**向量相加:** $\vec{a} + \vec{b} = \vec{c}$, $C = \sqrt{A^2 + B^2 + 2AB\cos(\theta)}$, $\theta$ 为 $\vec{a}$ 与 $\vec{b}$ 的夹角. (实际上为余弦定理)<br>

**向量加减:** $\vec{a} \pm \vec{b} = (A_x \pm B_x)\hat{i} + (A_y \pm B_y)\hat{j} + (A_z \pm B_z)\hat{k} $ <br> 

**平行向量:** $\vec{a} \neq 0$, 存在数$\lambda$, 使得 $\vec{b} = \lambda \vec{a}$, 则 $\vec{a} \parallel \vec{b}$, 即向量的对应
坐标成比例 <br>
$\vec{a} \times \vec{b} = 0 \iff \vec{a} \parallel \vec{b}$<br>

**向量点乘:** $\vec{a} \cdot \vec{b} = AB\cos(\theta)$, $\theta$ 为 $\vec{a}$ 与 $\vec{b}$ 的夹角. <br>
              $\vec{a} \cdot \vec{b} = A_x B_x + A_y B_y + A_z B_z$ <br>

**向量垂直:** $\vec{a} \perp \vec{b} \iff \vec{a} \cdot \vec{b} = 0 \iff x_1 x_2 + y_1 y_2 + z_1 z_2 = 0$ <br>

**向量的模:** $|\vec{a}| = \sqrt{x^2 + y^2 + z^2}$, $|\vec{a}| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}$ <br>

**向量夹角:** $\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos(\theta)$, $\cos(\theta) = \dfrac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \dfrac{x_1 x_2 + y_1 y_2 + z_1 z_2}{\sqrt{x_1^2 + y_1^2 + z_1^2} \sqrt{x_2^2 + y_2^2 + z_2^2}}$ <br>

**向量叉乘:** $\vec{C} = \vec{A} \times \vec{B}$, $\vec{C}$ 的大小为 $C = AB \sin{\theta}$, 方向符合右手螺旋法则.<br>
向量积的模表示以 $\vec{A}$ 和 $\vec{b}$ 为邻边的平行四边形面积.<br>
$\vec{A} \times \vec{b} = -\vec{B} \times \vec{A}$<br>

$\vec{a}\times\vec{b} = \begin{vmatrix}\hat{i} & \hat{j} & \hat{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z\end{vmatrix} = (A_yB_z - A_zB_y)\hat{i} - (A_xB_z - A_zB_x)\hat{j} + (A_xB_y - A_yB_x)\hat{k}$<br>

**单位向量关系:** $\hat{i} \cdot \hat{i} = \hat{j} \cdot \hat{j} = \hat{k} \cdot \hat{k} = 1$, $\hat{i} \cdot \hat{j} = \hat{i} \cdot \hat{k} = \hat{j} \cdot \hat{k} = 0$, 因为$\cos(0) = 1, \cos(\frac{\pi}{2}) = 0$ <br>
                  $\hat{i} \times \hat{j} = \hat{k}$, $\hat{j} \times \hat{k} = \hat{i},$ $\hat{k} \times \hat{j} = \hat{i}$, $\hat{i} \times \hat{i} = \hat{j} \times \hat{j} = \hat{k} \times \hat{k} = 0$<br>

**向量的混合积:** $(a \times b) \cdot c$, 记作 $[abc]$<br>
$(a \times b) = \begin{vmatrix}i & j & k \\ a_x & a_y & a_z \\ b_x & b_y & b_z\end{vmatrix} = \begin{vmatrix}a_y & a_z \\ b_y & b_z \end{vmatrix}i - \begin{vmatrix}a_x & a_z \\ b_x & b_z \end{vmatrix}j - \begin{vmatrix}a_x & a_y \\ b_x & b_y \end{vmatrix}k$<br>
$(a \times b) \cdot c = c_x\begin{vmatrix}a_y & a_z \\ b_y & b_z \end{vmatrix} - c_y\begin{vmatrix}a_x & a_z \\ b_x & b_z \end{vmatrix} - c_z\begin{vmatrix}a_x & a_y \\ b_x & b_y \end{vmatrix} = \begin{vmatrix}a_x & a_y & a_z \\ b_x & b_y & b_z \\ c_x & c_y & c_z\end{vmatrix}$ <br>
$[abc]$ 绝对值表示以向量a, b, c为棱的平行六面体的体积.<br>

**平面点法式方程**

平面上$\vec{M_0 M}=(x - x_0, y - y_9, z - z_0)$ 与该平面法向量$n=(A, B, C)$垂直, 因此 $n \cdot \vec{M_0 M} = 0$, <br>
$\Rightarrow A(x - x_0), B(y - y_0), C(c - z_0) = 0$, 即该平面的点法式方程.<br>

`e.g.` 求过三点 $M_1(2, -1, 4), M_2(-1, 3, -2), M_3(0, 2, 3)$ 的平面的方程.<br>
  - 将$M_1$带入 $A(x - x_0), B(y - y_0), C(c - z_0) = 0$ 得 $A(x - 2) + B(y + 1) + C (Z - 4)$, 对于任意平面上点点都满足此式, 计算出 A
    ,B 与 C 的关系, 再代入原式, 将 C 约掉, 得到平面方程.<br>
  - 得到向量 $\vec{M_1 M_2} = (-3, 4, -6), \vec{M_1 M_3} = (-2, 3, -1)$, 法向量$n = \vec{M_1 M_2} \times \vec{M_1 M_3} = 14i + 9j - k$, $\Rightarrow 14(x - 2) + 9(y + 1) - (z -4) = 0$.<br>

**平面一般方程**

拆开$A(x - x_0), B(y - y_0), C(c - z_0) = 0$括号, 令 $Ax_0 - By_0 - Cz_0 = D$, 得 $A_x + B_y + C_z + D = 0$, 即平面一般方程.<br>

`e.g` 求过 x 轴和点M(4, -3, -1) 的平面的方程.<br>

由过 x轴得 $n \perp x$轴, 由于法向量是自由向量, $\Rightarrow A = 0$, 平面一定过 x轴上任意一点, 一定过 (0, 0, 0), $\Rightarrow D = 0$,
$\Rightarrow  By + Cz = 0$, 将 M 带入得 $C = -3B$, $\Rightarrow By + (-3)Bz = 0$, 约掉 B, 得平面方程为 $y - 3z = 0$.<br>

**平面截距式方程**
