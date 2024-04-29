# midrash_multilabel_paleographical_feature_prediction_to_cluster_ASC_dataset
We designed a set of high priority paleographical features as a hierarchical multi-labeling classification problem that is a hierarchical tagging with multi-labels and mutually exclusive sub-labels shown in the following list:

\begin{itemize}
    \item \textbf{Label: nikud}
    \begin{itemize}
        \item nikud\_0
        \item nikud\_1
    \end{itemize}

    \item \textbf{Label: bited\_aleph}
    \begin{itemize}
        \item bited\_aleph\_0
        \item bited\_aleph\_1
    \end{itemize}

    \item \textbf{Label: fish\_tail}
    \begin{itemize}
        \item fish\_tail\_1
        \item fish\_tail\_2
    \end{itemize}

    \item \textbf{Label: short\_descender}
    \begin{itemize}
        \item short\_descender\_0
        \item short\_descender\_1
    \end{itemize}

    \item \textbf{Label: shading}
    \begin{itemize}
        \item shading\_0
        \item shading\_1
    \end{itemize}

    \item \textbf{Label: string}
    \begin{itemize}
        \item string\_1
        \item string\_2
    \end{itemize}

    \item \textbf{Label: left\_justify}
    \begin{itemize}
        \item left\_justify\_0
        \item left\_justify\_1
        \item left\_justify\_2
    \end{itemize}

    \item \textbf{Label: vertical\_stretch}
    \begin{itemize}
        \item vertical\_stretched\_0
        \item Vertical\_stretched\_1
    \end{itemize}

    \item \textbf{Label: left\_slanted}
    \begin{itemize}
        \item left\_slanted\_0
        \item left\_slanted\_1
    \end{itemize}

    \item \textbf{Label: nesting}
    \begin{itemize}
        \item nesting\_0
        \item nesting\_1
        \item nesting\_2
    \end{itemize}
\end{itemize}

Once we train a machine that can predict $n$ paleographical labels for a given text region, we plan to use all possible combinations of $1,2,3, ..., n$ features and find the optimal combinations that lead to the most cohesive clusters.

