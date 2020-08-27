---
layout: page
title: Tips
subtitle: Tips and Tricks
---

## GitHub Tips
- [Quick reference jekyll and Markdown](https://gist.github.com/roachhd/779fa77e9b90fe945b0c)
- [GitHub Pages](https://kipalog.com/posts/Kinh-nghiem-tao-website-ca-nhan-voi-Jekyll---Github-pages)



---
## SageMath Tips
- [Discrete Gaussian Samplers over the Integers](https://doc.sagemath.org/html/en/reference/stats/sage/stats/distributions/discrete_gaussian_integer.html). 
- [Discrete Gaussian Samplers for Integer Polynomials](https://doc.sagemath.org/html/en/reference/stats/sage/stats/distributions/discrete_gaussian_polynomial.html).
- [Discrete Gaussian Samplers over Lattices](https://doc.sagemath.org/html/en/reference/stats/sage/stats/distributions/discrete_gaussian_lattice.html).

---
## Tikz Tips

- **Tikz code for drawing cryptography box security games in Tikz**:

\documentclass[border=5pt,tikz]{standalone}
\usepackage{yfonts,amsmath,amssymb,amsfonts}
\usetikzlibrary{arrows,positioning,calc}
\begin{document}
    \begin{tikzpicture}[>=latex]
        \node[draw,inner sep=1.5cm] (a) {$A$};
        \node at (-7,0) (pk) {\textfrak{pk}};
            \draw[->] (pk) -- (a);
        \node[below=.2 of pk] (ms) {$m^*,s^*$};
            \draw[<-] (ms) --+ (5.35,0) node[midway,align=center,below,text width=4cm] {Win if \textsf{\textcolor{blue}{Verify$_{\textfrak{pk}}$}$(s^*,m^*)=\mathtt{valid}$ and $m^*\not\in\textcolor{red}{\mathcal{L}}$}};
            \node (n) at ([yshift=-.5cm,xshift=.5cm]a) {$m\in\mathbb{P}$};
            \draw[->] ($(n)+(1.15,0)$) --+ (2.8,0) node[midway,above] {$\mathcal{O}_{\textsf{Sig}_{\mathfrak{s\!k}}}$};
                \node[right] at ($(n)+(3.85,0)$) {$\textcolor{red}{\mathcal{L}}\leftarrow\textcolor{red}{\mathcal{L}}\cup\{m\}$};
            \draw[->] (4.4,-1) --+ (-2.75,0);
                \node[yshift=-.5cm,right] at ($(n)+(3.85,0)$) {$t\leftarrow\textcolor{red}{\textsf{Sig}_{\textcolor{blue}{\mathfrak{sk}}}}(m)$};
                \node[xshift=1.5cm,above=.5 of pk] {$(\textcolor{blue}{\mathfrak{pk}},\textcolor{red}{\mathfrak{sk}})\leftarrow\mathrm{KeyGen()}$};
                \node[xshift=11cm,above=.5 of pk] {$\textcolor{red}{\mathcal{L}}\leftarrow\emptyset$};
    \end{tikzpicture}
\end{document}

---
## Web of Science
- Search for journal's impact at [Web of Science](http://gots.uow.edu.au/gots/tutorial/web-of-science-advanced-search)


