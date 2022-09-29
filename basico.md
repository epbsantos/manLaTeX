# Primeiras linhas

```
\documentclass{article}

\begin{document}
Olá \LaTeX.

Os primeiros dois parágrafos.
\end{document}
```


# Simbolos reservados

```
# $ % ^ & _ { } ~ \
```

```
\# \$ \% \^{} \& \_ \{ \} \~{} \textbackslash{}
```


# Comentário (texto não processado)

```
...
% Este é um comentário em latex.
...
```

# Estrutura do documento
```
\documentclass[11pt,twoside,a4paper]{article}
```

<table class="wikitable">
<caption>Document Classes
</caption>
<tbody><tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">article </span>
</td>
<td>For articles in scientific journals, presentations, short reports, program documentation, invitations, ...
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">IEEEtran</span>
</td>
<td>For articles with the IEEE Transactions format.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">proc</span>
</td>
<td>A class for proceedings based on the article class.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">minimal</span>
</td>
<td>It is as small as it can get. It only sets a page size and a base font. It is mainly used for debugging purposes.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">report</span>
</td>
<td>For longer reports containing several chapters, small books, thesis, ...
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">book</span>
</td>
<td>For books.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">slides</span>
</td>
<td>For slides. The class uses big sans serif letters.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">memoir</span>
</td>
<td>For sensibly changing the output of the document. It is based on the <span style="font-family: monospace; color: #0000D0; font-weight: normal;">book</span> class, but you can create any kind of document with it <a rel="nofollow" class="external autonumber" href="http://www.ctan.org/tex-archive/macros/latex/contrib/memoir/memman.pdf">[1]</a>
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">letter</span>
</td>
<td>For writing letters.
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #0000D0; font-weight: normal;">beamer</span>
</td>
<td>For writing presentations (see <a href="/wiki/LaTeX/Presentations" title="LaTeX/Presentations">LaTeX/Presentations</a>).
</td></tr></tbody></table>

# Pacotes
```
\usepackage[options]{package}
```

# Comandos de sessões
Exemplo:
```
\chapter{Introduction}
This chapter's content...

\section{Structure}
This section's content...

\subsection{Top Matter}
This subsection's content...

\subsubsection{Article Information}
This subsubsection's content...
```

<table class="wikitable">
<tbody><tr>
<th>Command
</th>
<th width="10%">Level
</th>
<th>Comment
</th></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\part</span><span class="nb">{</span>''part''<span class="nb">}</span></code>
</td>
<td style="text-align: center">-1
</td>
<td>not in letters
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\chapter</span><span class="nb">{</span>''chapter''<span class="nb">}</span></code>
</td>
<td style="text-align: center">0
</td>
<td>only books and reports
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\section</span><span class="nb">{</span>''section''<span class="nb">}</span></code>
</td>
<td style="text-align: center">1
</td>
<td>not in letters
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\subsection</span><span class="nb">{</span>''subsection''<span class="nb">}</span></code>
</td>
<td style="text-align: center">2
</td>
<td>not in letters
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\subsubsection</span><span class="nb">{</span>''subsubsection''<span class="nb">}</span></code>
</td>
<td style="text-align: center">3
</td>
<td>not in letters
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\paragraph</span><span class="nb">{</span>''paragraph''<span class="nb">}</span></code>
</td>
<td style="text-align: center">4
</td>
<td>not in letters
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\subparagraph</span><span class="nb">{</span>''subparagraph''<span class="nb">}</span></code>
</td>
<td style="text-align: center">5
</td>
<td>not in letters
</td></tr>
</tbody></table>



