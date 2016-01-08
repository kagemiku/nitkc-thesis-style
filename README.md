# nitkc-thesis-style
Style file of LaTeX for graduation thesis at NIT, Kagoshima College.

# Style files
* **nitkc-proceeding**
* **nitkc-thesis**

## proceeding
* **proceeding/nitkc-proceeding.sty**

### Usage
#### `\myid` command
Adding ID prefix to page number in footer.
```tex
\myid{ID}
```

#### `\proctitle` command
Creation title of proceeding.
```tex
\proctitle{Title}{Your Name}{Supervisor Name}
```

## thesis
* **thesis/nitkc-thesis.sty**

### Usage
#### `\cover` command
Creation cover page.
```tex
\begin{document}
\cover{Title}{Student No}{Your Name}{Supervisor Name}{Filing date(day only)}
.
.
.
\end{document}
```

#### `\toc` command
Creation table of contents.
```tex
\begin{document}
.
\toc
.
.
.
\end{document}
```

# Author
KAGE

# Collaborator
[しんぷっと(@a0symptote)](https://twitter.com/a0symptote)

# License
MIT License
