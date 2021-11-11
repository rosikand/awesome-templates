# LaTeX Toolbox

I plan to use this space to jot down useful LaTeX commands, tips, tricks, and more. 

---

- For a horizontal rule, use `\noindent\rule[0.5ex]{\linewidth}{0.3pt}`. 
- For squishing text together to reduce page numbers, use [savetrees](https://ctan.org/pkg/savetrees?lang=en). 
  - To use it, simply add `\usepackage[subtle]{savetrees}` or `\usepackage[moderate]{savetrees}` or `\usepackage[extreme]{savetrees}`. 
- Typography is a big thing in LaTeX which is why the Microtype package is popular by producing text that is quite appealing to the eye. Read more [here](http://www.khirevich.com/latex/microtype/). 
- Put an `[H]` after `\begin{figure}` to force the position of the image where it appears in the source. You must also put `\usepackage{float}` in the preamble. 
- [Pandoc](https://pandoc.org/index.html) is a Markdown to LaTeX converter (that doesn't really quite work for my needs). Interestingly, it uses abstract syntax trees to 'parse' the input instead of making a translator. Read more [here](https://pandoc.org/scripting-1.12.html). 
  - The command for any file type to LaTeX is `pandoc -s input-file.md -o output-file.tex`.
- Check out this [markdown](https://www.overleaf.com/learn/how-to/Writing_Markdown_in_LaTeX_Documents) package. 
- `scrartcl`
- https://github.com/sloisel/pyptex
- kpfonts provides some nice serif fonts
