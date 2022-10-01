# Referência Bibliográfica


## <code>\label</code> e <code>\ref</code>
Quando é utilizado <code>\label{}</code>, pode ser referenciado com o <code>\ref{}</code>.
O <code>\label{}</code> pode ser usado para capítulos, figuras, tabelas, etc...

```latex
\section{Greetings}
\label{sec:greetings}

  Hello!

\section{Referencing}

  I greeted in section~\ref{sec:greetings}.
```

## <code>\cite</code>

[Gerenciador de bib - jabref](https://www.jabref.org/)

Para colocar uma citação bibliográfica, é utilizado o comando <code>\cite{key}</code> e é utilizado outro arquivo de bibliografia, o .bib!
