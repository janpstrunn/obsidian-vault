---
author: 
origin:
  - "[[Markdown]]"
source: 
tags:
  - manual
---

# Headings

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# F38BA8

## F3B387

### A6E3A1

#### 90E2D5

##### A0BEFE

###### CBA6F7

# Quotes

```markdown
> This is a callout
```

# Blockquotes

```markdown
> [!note]
> This is a blockcallout
```

## Blockquotes Types

> [!tldr] Abstract, summary, tldr

> [!info]

> [!todo]

> [!tip] Tip, hint, important

> [!success] Success, check, done

> [!question] Question, help, faq

> [!warning] Warning, caution, attention

> [!failure] Failure, fail, missing

> [!danger] Danger, error

> [!bug]

> [!example]

> [!quote] Quote, cite

> [!note]

> [!faq]- Foldable Callouts
> Surprise!

# Text Decoration

```markdown
**Bold**
*Italic*
==Highlight==
```

# Lists

```markdown
- Unordered list
	- Indented unordered list
	- Second line
1. Ordered list
	1. Indented ordered list
	2. Second line
- [ ] Task list
```

## Task List Statuses

- [/] Task
- [x] Task
- [-] Task
- [>] Task
- [<] Task
- [?] Task
- [!] Task
- [*] Task
- ["] Task
- [l] Task
- [b] Task
- [i] Task
- [S] Task
- [I] Task
- [p] Task
- [c] Task
- [f] Task
- [k] Task
- [w] Task
- [u] Task
- [x] Task

# Links

```markdown
[Link title](link url)
[DuckDuckGo](https://duckduckgo.com)
[Reference][1]
[1]: https://duckduckgo.com
```

# Inline Code and Code Blocks

```markdown
Inline `code`
Code Blocks have three backticks
```

# Tables

```markdown
Colons can be used to align columns.

| Table          | Header        | Text              |
| -------------- |:-------------:| -----------------:|
| Normal row     | Centered row  | Right-aligned row |
| Row 2, Col 1   | Row 3, Col 2  | **Bold**          |
| Row 3, Col 1   | Row 3, Col 2  |  *Italic*         |
```

# Horizontal Rules

```markdown
---
***
___
```

# Footnotes

```markdown
This is a simple footnote[^1]. 
[^1]: This is the referenced text. 
[^2]: Add 2 spaces at the start of each new line. This lets you write footnotes that span multiple lines. 
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.
```

# LaTeX

Reference: https://www.upyesp.org/posts/makrdown-vscode-math-notation/#postTOC

### Spacing

```latex
\!
\,
\:
\;
\
\quad
\qquad
```

### Arithmetic

| Notation                         | Example                                           | Inline                                                               | Code Block                        |
| -------------------------------- | ------------------------------------------------- | -------------------------------------------------------------------- | --------------------------------- |
| Addition                         | 𝑎+𝑏a+b                                          | `$a+b$`                                                              | `$$`  <br>`a+b`  <br>`$$`         |
| Subtraction                      | 𝑎−𝑏a−b                                          | `$a-b$`                                                              | `$$`  <br>`a-b`  <br>`$$`         |
| Various Forms of Multiplication  | 𝑎×𝑏a×b  <br>𝑎∗𝑏a∗b  <br>𝑎⋅𝑏a⋅b              | `$a \times b$`  <br>`$a \ast b$`  <br>`$a \cdot b$`                  | `$$`  <br>`a \cdot b`  <br>`$$`   |
| Various Forms of Division        | 𝑎:𝑏a:b  <br>𝑎/𝑏a/b  <br>𝑎÷𝑏a÷b  <br>𝑎𝑏ba​ | `$a \colon b$`  <br>`$a / b$`  <br>`$a \div b$`  <br>`$\frac{a}{b}$` | `$$`  <br>`a \div b`  <br>`$$`    |
| Remainder / Modulo               | 5mod2=15mod2=1                                    | `$5\mod 2=1$`                                                        | `$$`  <br>`5\mod 2=1`  <br>`$$`   |
| Negative Value                   | −𝑎−a                                             | `$-a$`                                                               | `$$`  <br>`-a`  <br>`$$`          |
| Plus or Minus, Minus or Plus     | ±𝑎±a  <br>∓𝑎∓a                                  | `$\pm a$`  <br>`$\mp a$`                                             | `$$`  <br>`\pm a`  <br>`$$`       |
| Squared, Cubed, nth-Power        | 𝑎2a2  <br>𝑎3a3  <br>𝑎𝑛an                      | `$a^2$`  <br>`$a^3$`  <br>`$a^n$`                                    | `$$`  <br>`a^3`  <br>`$$`         |
| Square Root, Cube Root, nth-Root | 𝑎a​  <br>𝑎33a​  <br>𝑎𝑛na​                     | `$\sqrt{a}$`  <br>`$\sqrt[3]{a}$`  <br>`$\sqrt[n]{a}$`               | `$$`  <br>`\sqrt[3]{a}`  <br>`$$` |

### Equality

|Notation|Example|Inline|Code Block|
|---|---|---|---|
|Equals|3=1+23=1+2|`$3=1+2$`|`$$`  <br>`3=1+2`  <br>`$$`|
|Not Equals|3≠43=4|`$3\neq4$`|`$$`  <br>`3\neq4`  <br>`$$`|
|Identical / Equivalent To|𝑎≡𝑏a≡b|`$a \equiv b$`|`$$`  <br>`a \equiv b`  <br>`$$`|
|Proportional To|𝑎∝𝑏a∝b|`$a \propto b$`|`$$`  <br>`a \propto b`  <br>`$$`|
|Approximately Equal To|sin⁡(0.01)≈0.01sin(0.01)≈0.01|`$\sin(0.01) \approx 0.01$`|`$$`  <br>`\sin(0.01) \approx 0.01`  <br>`$$`|

### Comparasion

| Notation                                                    | Example                | Inline                         | Code Block                     |
| ----------------------------------------------------------- | ---------------------- | ------------------------------ | ------------------------------ |
| a Less Than b  <br>a Greater Than b                         | 𝑎<𝑏a<b  <br>𝑎>𝑏a>b | `$a<b$`  <br>`$a>b$`           | `$$`  <br>`a<b`  <br>`$$`      |
| a Less Than or Equal To b  <br>a Greater Than or Equal To b | 𝑎≤𝑏a≤b  <br>𝑎≥𝑏a≥b | `$a \leq b$`  <br>`$a \geq b$` | `$$`  <br>`a \leq b`  <br>`$$` |
| a Much Smaller Than b  <br>a Much Larger Than b             | 𝑎≪𝑏a≪b  <br>𝑎≫𝑏a≫b | `$a \ll b$`  <br>`$a \gg b$`   | `$$`  <br>`a \ll b`  <br>`$$`  |

### Algebra

| Notation               | Example                                     | Inline                                                               | Code Block                                                                          |
| ---------------------- | ------------------------------------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Factorial              | 5!=5×4×3×2×15!=5×4×3×2×1                    | `$5!=5 \times 4 \times 3 \times 2 \times 1$`                         | `$$`  <br>`5!=5 \times 4 \times 3 \times 2 \times 1`  <br>`$$`                      |
| Absolute Value         | ∣−5∣=5∣−5∣=5                                | `$\|-5\|=5$`                                                         | `$$`  <br>`\|-5\|=5`  <br>`$$`                                                      |
| Function Of            | 𝑓(𝑥)=2𝑥2f(x)=2x2                         | `$f(x)=2x^2$`                                                        | `$$`  <br>`f(x)=2x^2`  <br>`$$`                                                     |
| Change or Difference   | Δ𝑥=𝑥1−𝑥0Δx=x1​−x0​                       | `$\Delta x = x_1 - x_0$`                                             | `$$`  <br>`\Delta x = x_1 - x_0`  <br>`$$`                                          |
| Pi                     | 𝜋=3.14159…π=3.14159…                       | `$\pi = 3.14159...$`                                                 | `$$`  <br>`\pi`  <br>`$$`                                                           |
| Euler’s Constant       | 𝑒=2.71828…e=2.71828…                       | `$e = 2.71828...$`                                                   | `$$`  <br>`e = 2.71828...`  <br>`$$`                                                |
| Sum                    | ∑𝑘=35𝑘2=32+42+52=50k=3∑5​k2=32+42+52=50   | `$\displaystyle\sum_{k=3}^5 k^2=3^2 + 4^2 + 5^2 =50$`                | `$$`  <br>`\displaystyle\sum_{k=3}^5 k^2=3^2 + 4^2 + 5^2 =50`  <br>`$$`             |
| Series Product         | ∏𝑥=24𝑥2=22×32×42=576x=2∏4​x2=22×32×42=576 | `$\displaystyle\prod_{x=2}^4 x^2 = 2^2 \times 3^2 \times 4^2 = 576$` | `$$`  <br>`\displaystyle\sum_{k=2}^4 k^2=2^2 \times 3^2 \times 4^2 = 576`  <br>`$$` |
| Brackets & Parentheses | […][…] (…)(…)                               | `$[\ldots] (\ldots)$`                                                | `$$`  <br>`[\ldots] (\ldots)`  <br>`$$`                                             |

### Angles

| Notation                 | Example                  | Inline                     | Code Block                                   |
| ------------------------ | ------------------------ | -------------------------- | -------------------------------------------- |
| Angle                    | ∠∠                       | `$\angle$`                 | `$$`  <br>`\angle`  <br>`$$`                 |
| Degree, Arc Min, Arc Sec | 30°45′30′′30°45′30′′     | `$30\degree45\rq30\rq\rq$` | `$$`  <br>`30\degree45\rq30\rq\rq`  <br>`$$` |
| Radians                  | 360°=2𝜋𝑟𝑎𝑑360°=2πrad | `$360\degree = 2\pi rad$`  | `$$`  <br>`360\degree = 2\pi rad`  <br>`$$`  |

### Probability and Statistics

| Notation                       | Example                    | Inline                                     | Code Block                                                   |
| ------------------------------ | -------------------------- | ------------------------------------------ | ------------------------------------------------------------ |
| Probability of Event A         | 𝑃(𝐴)P(A) or Pr⁡(𝐴)Pr(A) | `$P(A)$ or $\Pr(A)$`                       | `$$`  <br>`P(A)`  <br>`$$`                                   |
| Intersection Prob. of A & B    | 𝑃(𝐴∩𝐵)P(A∩B)            | `$P(A \cap B)$`                            | `$$`  <br>`P(A \ca pB)`  <br>`$$`                            |
| Union Prob. of A or B          | 𝑃(𝐴∪𝐵)P(A∪B)            | `$P(A \cup B)$`                            | `$$`  <br>`P(A \cup B)`  <br>`$$`                            |
| Conditional Prob. of A Given B | 𝑃(𝐴∣𝐵)P(A∣B)            | `$P(A\|B)$`                                | `$$`  <br>`P(A\|B)`  <br>`$$`                                |
| Median                         | 𝑥~x~                      | `$\tilde{x}$`                              | `$$`  <br>`\tilde{x}`  <br>`$$`                              |
| Population Mean                | 𝜇,𝑥‾,⟨𝑥⟩μ,x,⟨x⟩         | `$\mu , \overline{x} , \langle x \rangle$` | `$$`  <br>`\mu , \overline{x} , \langle x \rangle`  <br>`$$` |
| Standard Deviation             | 𝜎σ                        | `$\sigma$`                                 | `$$`  <br>`\sigma`  <br>`$$`                                 |
| Varience                       | 𝜎2σ2                      | `$\sigma^2$`                               | `$$`  <br>`\sigma^2`  <br>`$$`                               |

### Linear Algebra: Vectors

| Notation      | Example                                      | Inline                                                              | Code Block                                                                                          |
| ------------- | -------------------------------------------- | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Vectors       | 𝑣𝑣‾𝑣⃗vvv                                  | `$\mathbf{v}\overline{v}\vec{v}$`                                   | `$$`  <br>`\mathbf{v} \overline{v} \vec{v}`  <br>`$$`                                               |
| Row Vector    | 𝑣=(123)v=(1​2​3​)                           | `$v=\begin{pmatrix}1&2&3\end{pmatrix}$`                             | `$$`  <br>`v = \begin{pmatrix}`  <br>`1 & 2 & 3`  <br>`\end{pmatrix}`  <br>`$$`                     |
| Column Vector | 𝑤=(456)w=⎝⎛​456​⎠⎞​                         | `$w=\begin{pmatrix}4\cr5\cr6\cr\end{pmatrix}$`                      | `$$`  <br>`w=\begin{pmatrix}`  <br>`4 \cr`  <br>`5 \cr`  <br>`6 \cr`  <br>`\end{pmatrix}`  <br>`$$` |
| Dot Product   | 𝑣⋅𝑤v⋅w  <br>(𝑣,𝑤)(v,w)  <br><𝑣∣𝑤>⟨v∣w⟩ | `$\mathbf{v} \cdot \mathbf{w}$<br>$(v,w)$<br>$\left<v \| w\right>$` | `$$`  <br>`\mathbf{v}\cdot\mathbf{w}`  <br>`(v,w)`  <br>`\left<v\|w \right>`  <br>`$$`              |
| Cross Product | 𝑣×𝑤v×w                                     | `$v \times w$`                                                      | `$$`  <br>`v \times w`  <br>`$$`                                                                    |
| Length of v   | ∣𝑣∣∣v∣                                      | `$\|v\|$`                                                           | `$$`  <br>`\|v\|`  <br>`$$`                                                                         |
| Norm of v     | ∣∣𝑣∣∣∣∣v∣∣                                  | `$\|v\|$`                                                           | `$$`  <br>`\|v\|`  <br>`$$`                                                                         |

### Linear Algebra: Matrices

| Notation                                     | Example                  | Inline                                          | Code Block                                                                                                 |
| -------------------------------------------- | ------------------------ | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Matrix, 2 By 3                               | 𝐴=[123456]A=[14​25​36​] | `$A=\begin{bmatrix}1&2&3\cr4&5&6\end{bmatrix}$` | `$$`  <br>`A=`  <br>`\begin{bmatrix}`  <br>`1 & 2 & 3 \cr`  <br>`4 & 5 & 6`  <br>`\end{bmatrix}`  <br>`$$` |
| Product                                      | 𝐴⋅𝐵A⋅B                 | `$A \cdot B$`                                   | `$$`  <br>`A \cdot B`  <br>`$$`                                                                            |
| Hadamard Product                             | 𝐴∘𝐵A∘B                 | `$A \circ B$`                                   | `$$`  <br>`A \circ B`  <br>`$$`                                                                            |
| Kronecker Product                            | 𝐴⊗𝐵A⊗B                 | `$A \otimes B$`                                 | `$$`  <br>`A \otimes B`  <br>`$$`                                                                          |
| Transposed Matrix                            | 𝐴𝑇AT                   | `$A^T$`                                         | `$$`  <br>`A^T`  <br>`$$`                                                                                  |
| Hermitian Matrix or  <br>Conjugate Transpose | 𝐴†A†  <br>𝐴∗A∗         | `$A^\dag$`  <br>`$A^\ast$`                      | `$$`  <br>`A^\dag`  <br>`A^\ast`  <br>`$$`                                                                 |
| Inverse Matrix                               | 𝐴−1A−1                  | `$A^{-1}$`                                      | `$$`  <br>`A^{-1}`  <br>`$$`                                                                               |
| Determinant                                  | ∣𝐴∣∣A∣                  | `$\|A\|$`                                       | `$$`  <br>`\|A\|`  <br>`$$`                                                                                |
| Norm                                         | ∣∣𝐴∣∣∣∣A∣∣              | `$\|A\|$`                                       | `$$`  <br>`\|A\|`  <br>`$$`                                                                                |

### Calculus

| Notation                                              | Example                     | Inline                            | Code Block                                          |
| ----------------------------------------------------- | --------------------------- | --------------------------------- | --------------------------------------------------- |
| Example Function:  <br>𝑦=𝑥24y=4x2​                  | 𝑦=𝑥24y=4x2​               | `$y = \frac{x^2}{4}$`             | `$$`  <br>`y = \frac{x^2}{4}`  <br>`$$`             |
| Integration  <br>(Limits: 1 to 4)                     | 𝐴=∫14𝑥2𝑥𝑑𝑥A=∫14​xx2​dx | `$A = \int_1^4 \frac{x^2}{x} dx$` | `$$`  <br>`A = \int_1^4 \frac{x^2}{x} dx`  <br>`$$` |
| Differentiation                                       |                             |                                   |                                                     |
| First Derivative  <br>With Respect To 𝑥x             | 𝑑𝑓𝑑𝑥dxdf​               | `$\frac{df}{dx}$`                 | `$$`  <br>`\frac{df}{dx}`  <br>`$$`                 |
| Partial Derivative  <br>With Respect To 𝑥x           | ∂𝑓∂𝑥∂x∂f​                 | `$\frac{\partial f}{\partial x}$` | `$$`  <br>`\frac{\partial f}{\partial x}`  <br>`$$` |
| First and Second Derivative  <br>of Function          | 𝑓′f′  <br>𝑓′′f′′          | `$f\rq$`  <br>`$f\rq\rq$`         | `$$`  <br>`f\rq`  <br>`f\rq\rq`  <br>`$$`           |
| First and Second Derivative  <br>With Respect To Time | 𝑓˙f˙​  <br>𝑓¨f¨​          | `$\dot f$`  <br>`$\ddot f$`       | `$$`  <br>`\dot f`  <br>`\ddot f`  <br>`$$`         |

### Complex Numbers

| Notation                         | Example                             | Inline                                       | Block                                                        |
| -------------------------------- | ----------------------------------- | -------------------------------------------- | ------------------------------------------------------------ |
| Imaginary Unit 𝑖i               | 𝑧=3+2𝑖z=3+2i                      | `$z=3+2i$`                                   | `$$`  <br>`z=3+2i`  <br>`$$`                                 |
| Real Part Of Complex Number      | ℜ(𝑧)=3ℜ(z)=3  <br>Re⁡(𝑧)=3Re(z)=3 | `$\Re(z)=3$`  <br>`$\operatorname{Re}(z)=3$` | `$$`  <br>`\Re(z)=3`  <br>`\operatorname{Re}(z)=3`  <br>`$$` |
| Imaginary Part Of Complex Number | ℑ(𝑧)=2ℑ(z)=2  <br>Im⁡(𝑧)=2Im(z)=2 | `$\Im(z)=2$`  <br>`$\operatorname{Im}(z)=2$` | `$$`  <br>`\Im(z)=2`  <br>`\operatorname{Im}(z)=2`  <br>`$$` |
| Complex Conjugate                | 𝑧ˉ=𝑧∗=3−2𝑖zˉ=z∗=3−2i             | `$\bar{z}=z^*=3-2i$`                         | `$$`  <br>`\bar{z}=z^*=3-2i`  <br>`$$`                       |

### Greek Alphabet

| Letter  | Lower | Inline       | Inline       |
| ------- | ----- | ------------ | ------------ |
| Alpha   | 𝛼α   | `$\alpha$`   | `$\Alpha$`   |
| Beta    | 𝛽β   | `$\beta$`    | `$\Beta$`    |
| Gamma   | 𝛾γ   | `$\gamma$`   | `$\Gamma$`   |
| Delta   | 𝛿δ   | `$\delta$`   | `$\Delta$`   |
| Epsilon | 𝜖ϵ   | `$\epsilon$` | `$\Epsilon$` |
| Zeta    | 𝜁ζ   | `$\zeta$`    | `$\Zeta$`    |
| Eta     | 𝜂η   | `$\eta$`     | `$\Eta$`     |
| Theta   | 𝜃θ   | `$\theta$`   | `$\Theta$`   |
| Iota    | 𝜄ι   | `$\iota$`    | `$\Iota$`    |
| Kappa   | 𝜅κ   | `$\kappa$`   | `$\Kappa$`   |
| Lambda  | 𝜆λ   | `$\lambda$`  | `$\Lambda$`  |
| Mu      | 𝜇μ   | `$\mu$`      | `$\Mu$`      |
| Nu      | 𝜈ν   | `$\nu$`      | `$\Nu$`      |
| Xi      | 𝜉ξ   | `$\xi$`      | `$\Xi$`      |
| Omicron | 𝜊ο   | `$\omicron$` | `$\Omicron$` |
| Pi      | 𝜋π   | `$\pi$`      | `$\Pi$`      |
| Rho     | 𝜌ρ   | `$\rho$`     | `$\Rho$`     |
| Sigma   | 𝜎σ   | `$\sigma$`   | `$\Sigma$`   |
| Tau     | 𝜏τ   | `$\tau$`     | `$\Tau$`     |
| Upsilon | 𝜐υ   | `$\upsilon$` | `$\Upsilon$` |
| Phi     | 𝜙ϕ   | `$\phi$`     | `$\Phi$`     |
| Chi     | 𝜒χ   | `$\chi$`     | `$\Chi$`     |
| Psi     | 𝜓ψ   | `$\psi$`     | `$\Psi$`     |
| Omega   | 𝜔ω   | `$\omega$`   | `$\Omega$`   |
