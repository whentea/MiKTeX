# Hay...  
Firstly, download your MiKTeX via the following link  
[Click the link on !](https://miktex.org/download)

1. The basic layout of a LaTeX file  
```
\documentclass{article} %LaTeX code
\begin{document} %LaTeX code
 Hello Guys ! %Actual content
\end{document} %LaTeX code
```  
% is a comment sign that will not be executed by the program.  
\commandname{option} is an instruction or command for the LaTeX compiler.  
2. An Environment  
```
\begin{document}
 \begin{environment1}
  \begin{environment2}
  \end{environment2}
 \end{environment1}
\end{document}
```   
An environment is simply an area of your document where certain typesetting rules apply.
3. Adding a tittle page  
```
\documentclass{article}

\title{My first article} %preamble
\date{May 5th, 2019} %preamble
\author{whentea} %preamble

\begin{document}
 \maketitle %presenting the preamble
 \newpage %make a new page
   Hello Guys !!
\end{document}
```  
```
\documentclass{article}

\title{My first article}
\date{May 5th, 2019}
\author{whentea}

\begin{document}
 \pagenumbering{gobble} %telling LaTeX to hide the page number of our first page
 \maketitle
 \newpage
 \pagenumbering{arabic} %changing it back to arabic on the next page numbers
 Hello Guys !!
\end{document}
```




