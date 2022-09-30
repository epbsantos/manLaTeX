# Tabela

A criação de tabelas no latex pode ser complicado, pela forma bidimencional da informação e oganizar isso em um texto corrido. Sugiro usar o site para ajudar:

<a href="https://www.tablesgenerator.com/" target="_blank">tablesgenerator</a>

**Configurações**
<table class="wikitable">
<tbody><tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">l</span>
</td>
<td>left-justified column
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">c</span>
</td>
<td>centered column
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">r</span>
</td>
<td>right-justified column
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">p{'width'}</span>
</td>
<td>paragraph column with text vertically aligned at the top
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">m{'width'}</span>
</td>
<td>paragraph column with text vertically aligned in the middle (requires array package)
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">b{'width'}</span>
</td>
<td>paragraph column with text vertically aligned at the bottom (requires array package)
</td></tr>
<tr>
<td><tt>|</tt>
</td>
<td>vertical line
</td></tr>
<tr>
<td><tt>||</tt>
</td>
<td>double vertical line
</td></tr></tbody></table>

**Alinhamento vertical**

Dentro dos []
```latex
\begin{tabular}[pos]{table spec}
```
<table class="wikitable">

<tbody><tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">b</span>
</td>
<td>bottom
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">c</span>
</td>
<td>center (default)
</td></tr>
<tr>
<td><span style="font-family: monospace; color: #C08020; font-weight: normal;">t</span>
</td>
<td>top
</td></tr>
</tbody></table>

**Separadores e quebras**
<table class="wikitable">
<tbody><tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="nb">&amp;</span></code>
</td>
<td>column separator
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\\</span></code>
</td>
<td>start new row (additional space may be specified after <code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\\</span></code> using square brackets, such as <span style="font-family: monospace; color: #C08020; font-weight: normal;">\\[6pt]</span>)
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\hline</span></code>
</td>
<td>horizontal line
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\newline</span></code>
</td>
<td>start a new line within a cell (in a paragraph column)
</td></tr>
<tr>
<td><code class="mw-highlight mw-highlight-lang-latex mw-content-ltr" dir="ltr"><span class="k">\cline</span><span class="nb">{</span>i-j<span class="nb">}</span></code>
</td>
<td>partial horizontal line beginning in column <i>i</i> and ending in column <i>j</i>
</td></tr></tbody></table>


## Exemplo
```latex
\begin{tabular}{ l c r }
  001 & 002 & 003 \\
   04 &  05 &  06 \\
    7 &   8 &   9 \\
\end{tabular}
```

