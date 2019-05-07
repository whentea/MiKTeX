### Packages and Math
LaTeX offers a lot of functions BY DEFAULT.  
You simply add the \usepackage directive to preamble of your document.  
The most useful package is an equation, a typsetting math in LaTeX.

There are two major modes of typesetting math in LaTeX.

**Exercise 1 : xxx.tex script without math package**
 ```
 \documentclass{article}

\title{my math document}
\date{May 7, 2019}
\author{whentea}


\begin{document}
\pagenumbering{gobble}
\maketitle
\newpage
\pagenumbering{arabic}

\begin{equation}
f(x) = x^2
\end{equation}
\end{document}
 ```
 
**Excercise 2 : xxx.tex script using math package**
 
 ```
 \documentclass{article}

\title{my math document}
\date{May 7, 2019}
\author{whentea}

\usepackage{amsmath}


\begin{document}
\pagenumbering{gobble}
\maketitle
\newpage
\pagenumbering{arabic}

\begin{equation*}
f(x) = x^2
\end{equation*}
\end{document}
 ```
 
 **Excercise 3 : xxx.tex script using math package**
 ```
 \documentclass{article}

\usepackage{amsmath}

\begin{document}

\begin{align*}
  f(x) &= x^2\\
  g(x) &= \frac{1}{x}\\
  F(x) &= \int^a_b \frac{1}{3}x^3
\end{align*}

\begin{equation*}
\left[
\begin{matrix}
1 & 0\\
0 & 1
\end{matrix}
\right]
\end{equation*}

\begin{equation*}
\frac{1}{\sqrt{x}}
\end{equation*}

\begin{equation*}
\left(\frac{1}{\sqrt{x}}\right)
\end{equation*}

\begin{equation*}
\frac{1}{\sqrt{x}}
\end{equation*}

\begin{equation*}
\lambda
\end{equation*}


This formula $f(x) = x^2$\\
\\
$\sum_{n=1}^{\infty} \frac{1}{n}$, not this $\sum_{n=1}^{\infty} \frac{1}{n}$
\\
\[x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\]


\end{document}
 ```
 
 
 