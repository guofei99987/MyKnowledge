
## 上下标
- $a^{-\alpha}_{ij}$
- 也可以换顺序： $e_{k_1}^{x^2}$
- 有时大括号可以省略： $a_i^kw$ ，这时有效范围是单字母和1位数字。



## 分数
- $\frac{a_1}{b_1}$

![2](assets/2.png)
3:
![3](assets/3.png)
|||
|--|--|
|$\Leftrightarrow$|Leftrightarrow|$\leftrightarrow$|leftrightarrow|
|$\Leftarrow$|Leftarrow|$\leftarrow$|leftarrow|
|$\Rightarrow$|Rightarrow|$\rightarrow$|rightarrow|
|$\Longleftrightarrow$|Longleftrightarrow|...|
![4](assets/4.png)

![5](assets/5.png)


![6](assets/6.png)


![7](assets/7.png)






## 大括号
方法一：
$$ f(x)=\left\{
\begin{aligned}
x & = & \cos(t) \\
y & = & \sin(t) \\
z & = & \frac xy
\end{aligned}
\right.
$$

方法二：
$$ F^{HLLC}=\left\{
\begin{array}{rcl}
F_L       &      & {0      <      S_L}\\
F^* _ L     &      & {S_L \leq 0 < S_M}\\
F^* _ R     &      & {S_M \leq 0 < S_R}\\
F_R       &      & {S_R \leq 0}
\end{array} \right. $$

{}居中
lcl 居左
ccc 居中
rcl 右对齐

嵌套：
$$
\begin{array}{rcl}
F_L       &      & {0      <      S_L}\\
F^* _ L     &      & {S_L \leq 0 < S_M}\\
F^* _ R     &      & {S_M \leq 0 < S_R}\\
\left\{ \begin{array}{rcl}
F_L       &      & {0      <      S_L}\\
F^* _ L     &      & {S_L \leq 0 < S_M}\\
F^* _ R     &      & {S_M \leq 0 < S_R}\\
F_R       &      & {S_R \leq 0}
\end{array} \right.
\end{array}  $$


方法三:
$$f(x)=
\begin{cases}
0& \text{x=0}\\
1& \text{x!=0}
\end{cases}$$

## 矩阵和行列式


$
 \left ( \begin{array}{ccc}
a & b & c \\
d & e & f \\
g & h & i \end{array} \right ) $


$
 \left | \begin{array}{ccc}
a & b & c \\
d & e & f \\
g & h & i \end{array} \right | $


---

* 结束
.

# Latex中的希腊字母

<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>希腊字母</th><th>LaTeX形式</th><th>希腊字母</th><th>LaTeX形式</th></tr></thead><tbody>
 <tr><td>α A</td><td>\alpha A</td><td>μ N</td><td>\mu N</td></tr>
 <tr><td>β B</td><td>\beta B</td><td>ξ Ξ</td><td>\xi \Xi</td></tr>
 <tr><td>γ Γ</td><td>\gamma \Gamma</td><td>o O</td><td>o O</td></tr>
 <tr><td>δ Δ</td><td>\delta \ Delta</td><td>π Π</td><td>\pi \Pi</td></tr>
 <tr><td>ϵ ε E</td><td>\epsilon \varepsilon E</td><td>ρ ϱ P</td><td>\rho \varrho P</td></tr>
 <tr><td>ζ Z</td><td>\zeta Z</td><td>σ Σ</td><td>\sigma \Sigma</td></tr>
 <tr><td>η H</td><td>\eta H</td><td>τ T</td><td>\tau T</td></tr>
 <tr><td>θ ϑ Θ</td><td>\theta \vartheta \Theta</td><td>υ Υ</td><td>\upsilon \Upsilon</td></tr>
 <tr><td>ι I</td><td>\iota I</td><td>ϕ φ Φ</td><td>\phi \varphi \Phi</td></tr>
 <tr><td>κ K</td><td>\kappa K</td><td>χ X</td><td>\chi X</td></tr>
 <tr><td>λ Λ</td><td>\lambda \Lambda</td><td>ψ Ψ</td><td>\psi \Psi</td></tr>
 <tr><td>μ M</td><td>\mu M</td><td>ω Ω</td><td>\omega \Omega</td></tr>
</tbody></table>

# 希腊字母

<table class="tableizer-table">
<thead><tr class="tableizer-firstrow"><th>字母名称</th><th>大写字母</th><th>小写字母</th><th>字母名称</th><th>大写字母</th><th>小写字母</th></tr></thead><tbody>
 <tr><td>alpha</td><td>Α</td><td>α</td><td>nu</td><td>Ν</td><td>ν</td></tr>
 <tr><td>beta</td><td>Β</td><td>β</td><td>xi</td><td>Ξ</td><td>ξ</td></tr>
 <tr><td>gamma</td><td>Γ</td><td>γ</td><td>omicron</td><td>Ο</td><td>ο</td></tr>
 <tr><td>delta</td><td>Δ</td><td>δ</td><td>pi</td><td>Π</td><td>π</td></tr>
 <tr><td>epsilon</td><td>Ε</td><td>ε</td><td>rho</td><td>Ρ</td><td>ρ</td></tr>
 <tr><td>zeta</td><td>Ζ</td><td>ζ</td><td>sigma</td><td>Σ</td><td>σ ς</td></tr>
 <tr><td>eta</td><td>Η</td><td>η</td><td>tau</td><td>Τ</td><td>τ</td></tr>
 <tr><td>theta</td><td>Θ</td><td>θ</td><td>upsilon</td><td>Υ</td><td>υ</td></tr>
 <tr><td>iota</td><td>Ι</td><td>ι ℩</td><td>phi</td><td>Φ</td><td>φ</td></tr>
 <tr><td>kappa</td><td>Κ</td><td>κ</td><td>chi</td><td>Χ</td><td>χ</td></tr>
 <tr><td>lambda</td><td>Λ</td><td>λ</td><td>psi</td><td>Ψ</td><td>ψ</td></tr>
 <tr><td>mu</td><td>Μ</td><td>μ</td><td>omega</td><td>Ω</td><td>ω</td></tr>
</tbody></table>
