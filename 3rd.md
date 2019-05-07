### Packages and Math
LaTeX offers a lot of functions BY DEFAULT.  
You simply add the \usepackage directive to preamble of your document.  
The most useful package is an equation, a typsetting math in LaTeX.

There are two major modes of typesetting math in LaTeX.

**xxx.tex script without math package**
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
 
**xxx.tex script using math package**
 
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