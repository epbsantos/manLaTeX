# Figura

<a href="https://app.diagrams.net/" target="_blank">draw.io (editor de diagrama online)</a>

```latex
\begin{figure}[placement specifier]
... figure contents ...
\end{figure}
```

<table class="wikitable">
<tbody><tr>
<th>Specifier
</th>
<th>Permission
</th></tr>
<tr>
<td><code>h</code>
</td>
<td>Place the float <i>here</i>, i.e., <i>approximately</i> at the same point it occurs in the source text (however, not <i>exactly</i> at the spot)
</td></tr>
<tr>
<td><code>t</code>
</td>
<td>Position at the <i>top</i> of the page.
</td></tr>
<tr>
<td><code>b</code>
</td>
<td>Position at the <i>bottom</i> of the page.
</td></tr>
<tr>
<td><code>p</code>
</td>
<td>Put on a special <i>page</i> for floats only.
</td></tr>
<tr>
<td><code>!</code>
</td>
<td>Override internal parameters LaTeX uses for determining "good" float positions.
</td></tr>
<tr>
<td><code>H</code>
</td>
<td>Places the float at precisely the location in the LaTeX code. Requires the <span style="font-family: monospace; color: #2020C0; font-weight: normal;">float</span> package,<sup id="cite_ref-1" class="reference"><a href="#cite_note-1">[1]</a></sup> i.e., <code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\usepackage</span><span class="nb">{</span>float<span class="nb">}</span></code>.
</td></tr></tbody></table>

## Dentro do _figure_
```latex
  \centering
  \label{fig:picture}
  \caption{ ... caption text ... }
  \includegraphics[width=0.9\textwidth]{picture}% picture filename
```

## Sub-figuras
```latex
\usepackage{graphicx}
\usepackage{subcaption}

\begin{figure}
    \centering
    \begin{subfigure}[b]{0.3\textwidth}
        \includegraphics[width=\textwidth]{gull}
        \caption{A gull}
        \label{fig:gull}
    \end{subfigure}
    ~ %add desired spacing between images, e. g. ~, \quad, \qquad, \hfill etc. 
      %(or a blank line to force the subfigure onto a new line)
    \begin{subfigure}[b]{0.3\textwidth}
        \includegraphics[width=\textwidth]{tiger}
        \caption{A tiger}
        \label{fig:tiger}
    \end{subfigure}
    ~ %add desired spacing between images, e. g. ~, \quad, \qquad, \hfill etc. 
    %(or a blank line to force the subfigure onto a new line)
    \begin{subfigure}[b]{0.3\textwidth}
        \includegraphics[width=\textwidth]{mouse}
        \caption{A mouse}
        \label{fig:mouse}
    \end{subfigure}
    \caption{Pictures of animals}\label{fig:animals}
\end{figure}
```
