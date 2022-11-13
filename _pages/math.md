# Math
MarkNote supports rendering mathematics in both inline mode and block mode.  The rendering is processed by [MathJax](https://www.mathjax.org).
To create an inline formula, just wrapper your formula with `$`. For example,   `$ E=mc^2 $`  should be rendered as  $ E = mc^2  $

Similarly, to create a formula block, just wrapper your formula with `$$`.
MarkNote supports 3 types of Math notation: AsciiMath, Tex/LaTeX and MathML. 
#### AsciiMath
Check [here](http://www1.chapman.edu/~jipsen/mathml/asciimathsyntax.html) for AsciiMath syntax.
Sample:
Code:
```
$$
sum_(i=1)^n i^3=((n(n+1))/2)^2
$$
```
Will be rendered as:
$$
sum_(i=1)^n i^3=((n(n+1))/2)^2
$$

#### TeX, LaTeX
You could find the all supported TeX/LaTeX commands [here](http://docs.mathjax.org/en/latest/tex.html#supported-latex-commands)
Sample:
Code:
```
$$
\displaystyle x = \frac{ - b \pm \displaystyle\sqrt {b^2 - 4ac} }{2a}
\ {\text{ when}}\ {ax^2 + bx + c = 0}
$$
```
will be rendered as:
$$
\displaystyle x = \frac{ - b \pm \displaystyle\sqrt {b^2 - 4ac} }{2a}
\ {\text{ when}}\ {ax^2 + bx + c = 0}
$$

#### MathML
Please check [here](http://docs.mathjax.org/en/latest/mathml.html#supported-mathml-commands) for the MathML support details.