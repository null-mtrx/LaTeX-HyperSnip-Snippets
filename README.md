# LaTeX Hypersnip Snippets

## Introduction
A bunch of $\LaTeX$ snippets which have massively sped up my workflow when working with $\LaTeX$ on VS Code.

## Set up 
To set up the config, first install the <a href="https://marketplace.visualstudio.com/items?itemName=draivin.hsnips">hypersnips</a> extension of VS Code
```bash
git clone https://github.com/null-mtrx/LaTeX-HyperSnip-Snippets

cd .../LaTeX-HyperSnip-Snippets

cp latex.hsnips ~/.config/Code/User/globalStorage/draivin.hsnips/hsnips

```

After doing so, restart VS Code

## Snippet Documentation
### Math Environment
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | Inline math mode | `mk` | `$...$` |
| 2 | Display math mode | `dk` | `\[ ... \]` |
| 3 | Align environment | `qj` | `\begin{align} ... \end{align}` |

> [!NOTE]
> The following snippets will only activate when typed in a math environment as shown above

### Basic Math Symbols

| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | Implies / Right arrow | `=> ` | $\Rightarrow$ |
| 2 | If and only if / Equivalent | `<=>` | $\iff$ |
| 3 | To / Maps to arrow | `-> ` | $\to$ |
| 4 | Times / Multiplication symbol | `* ` | $\times$ |
| 5 | Fraction simple | `<a>/<b>` | $\frac{a}{b}$ |
| 6 | Fraction auto-capture (with parentheses) | `(<a+b>)/` | $\frac{a+b}{...}$ |
|7|Power/Superscript| `<a>^<b + c>` | $a^{b + c}$
| 9 | Infinity | `oo` | $\infty$ |
| 10 | Square root | `sqrt` | $\sqrt{\dots}$ |
| 11 | Left-Right parentheses | `lrp` | $\left(\dots\right)$ |
| 12 | Left-Right square brackets | `lrb` | $\left[\dots\right]$ |
| 13 | Left-Right vertical bars (Magnitude/Absolute value) | `lrm` | $\left\|\dots\right\|$ |
| 14 | Left-Right curly braces | `lrc` | $\{\dots\}$ |

### Basic Logic and Set Notation
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | Maps to | `\|-` | $\mapsto$ |
| 2 | Element of / In | `<-` | $\in$ |
| 3 | Greater than or equal to | `>=` | $\geq$ |
| 4 | Less than or equal to | `<= ` | $\leq$ |
| 5 | Logical negation / Not | `neg` | $\neg$ |
| 6 | Logical conjunction / And | `<space>^<space>` | $\land$ |
| 7 | Logical disjunction / Or | `<space>:V<space>` | $\lor$ |
| 8 | Subset | `subs` | $\subset$ |
| 9 | Subset or equal to | `sub=` | $\subseteq$ |
| 10 | Union | `!U` | $\cup$ |
| 11 | Intersection | `!C` | $\cap$ |
|12 | Approximately equal to | `~` | $\approx$ |
| 13 | For all / Universal quantifier | `fa` | $\forall$ |

### Trigonometry and Logarithms
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | Sine function | `sin ` | $\sin\left(\dots\right)$ |
| 2 | Cosine function | `cos` | $\cos\left(\dots\right)$ |
| 3 | Tangent function | `tan` | $\tan\left(\dots\right)$ |
| 4 | Secant function | `sec` | $\sec\left(\dots\right)$ |
| 5 | Cosecant function | `csc` | $\csc\left(\dots\right)$ |
| 6 | Cotangent function | `cot ` | $\cot\left(\dots\right)$ |
| 7 | Sine with auto exponent | `sin<exp>` | $\sin^{\text{exp}}\left(\dots\right)$ |
| 8 | Cosine with auto exponent | `cos<exp>` | $\cos^{\text{exp}}\left(\dots\right)$ |
| 9 | Tangent with auto exponent | `tan<exp>` | $\tan^{\text{exp}}\left(\dots\right)$ |
| 10 | Cosecant with auto exponent | `csc<exp>` | $\csc^{\text{exp}}\left(\dots\right)$ |
| 11 | Secant with auto exponent | `sec<exp>` | $\sec^{\text{exp}}\left(\dots\right)$ |
| 12 | Cotangent with auto exponent | `cot<exp>` | $\cot^{\text{exp}}\left(\dots\right)$ |
| 13 | Exponential function | `exp` | $\exp\left(\dots\right)$ |
| 14 | Logarithm with auto base | `log<base>` | $\log_{\text{base}}\left(\dots\right)$ |
| 15 | Natural logarithm | `ln` | $\ln\left(\dots\right)$ |

### Greek Letters
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | alpha | `@a` | $\alpha$ |
| 2 | beta | `@b` | $\beta$ |
| 3 | Gamma | `@G` | $\Gamma$ |
| 4 | gamma | `@g` | $\gamma$ |
| 5 | Delta | `@D` | $\Delta$ |
| 6 | delta | `@d` | $\delta$ |
| 7 | epsilon | `@e` | $\epsilon$ |
| 8 | zeta | `@z` | $\zeta$ |
| 9 | eta | `@h` | $\eta$ |
| 10 | Theta | `@T` | $\Theta$ |
| 11 | theta | `@t` | $\theta$ |
| 12 | iota | `@i` | $\iota$ |
| 13 | kappa | `@k` | $\kappa$ |
| 14 | Lambda | `@L` | $\Lambda$ |
| 15 | lambda | `@l` | $\lambda$ |
| 16 | mu | `@m` | $\mu$ |
| 17 | nu | `@n` | $\nu$ |
| 18 | Xi | `@X` | $\Xi$ |
| 19 | xi | `@x` | $\xi$ |
| 20 | omicron | `@o` | $\omicron$ |
| 21 | Pi | `@P` | $\Pi$ |
| 22 | pi | `@p` | $\pi$ |
| 23 | rho | `@r` | $\rho$ |
| 24 | Sigma | `@S` | $\Sigma$ |
| 25 | sigma | `@s` | $\sigma$ |
| 26 | tau | `@u` | $\tau$ |
| 27 | Phi | `@F` | $\Phi$ |
| 28 | phi | `@f` | $\phi$ |
| 29 | chi | `@c` | $\chi$ |
| 30 | Psi | `@Y` | $\Psi$ |
| 31 | psi | `@y` | $\psi$ |
| 32 | Omega | `@W` | $\Omega$ |
| 33 | omega | `@w` | $\omega$ |

### Other Letter Formats
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | blackboard letter | `:L` | $\mathbb{L}$ |
| 2 | caligraphy letter | `;L` | $\mathcal{L}$ |

### Calculus and Summation
| Sno. | Snippet name (What the snippet is for) | Snippet format (like what to type to activate it) | Snippet output in LaTeX |
| :--- | :--- | :--- | :--- |
| 1 | First derivative with respect to x | `ddx` | $\frac{d \dots}{dx}$ |
| 2 | Higher-order derivative | `d<order>d<var>` | $\frac{d^{\text{order}} \dots}{d\text{var}^{\text{order}}}$ |
| 3 | Definite integral with auto variable | `int<lower>d<var>` | $\int_{\text{lower}}^{\dots} \dots d\text{var}$ |
| 4 | Limit with auto variable | `lim<var>` | $\lim_{\text{var} \to \dots} \dots$ |
| 5 | Higher-order partial derivative | `pr<order>pr<var>` | $\frac{\partial^{\text{order}} \dots}{\partial \text{var}^{\text{order}}}$ |
| 6 | Partial derivative with respect to x^power | `prpr<power>` | $\left(\frac{\partial \dots}{\partial x}\right)^{\text{power}}$ |
| 7 | Summation with auto lower bound | `sum<lower>` | $\sum_{i = \text{lower}}^{\dots} \dots$ |
