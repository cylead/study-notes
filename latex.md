## graph
\usepackage{graphicx}

\graphicspath{ {./images/} }

\begin{figure}
\center
\includegraphics[scale=0.5]{?.png}
\caption{?}
\label{?}
\end{figure}

## citation
citation.bib  
\cite{}
\bibliographystyle{ieeetr}
\bibliography{refs} 

In vscode, remember to click Recipe:pdflatex -> bibtex -> pdflatx*2, then Recipe:xelatex

## text mark
### textsubscript
\usepackage{fixltx2e}

a\textsubscript{b}
### hat
\hat{a}, \widehat{a}
## list 

\begin{itemize}
    \item a
    \item b
\end{itemize}

\begin{enumerate}
    \item a
    \item b
\end{enumerate}
