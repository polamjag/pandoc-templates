## building markdown
```
pandoc -f markdown+inline_notes+footnotes+definition_lists --latex-engine=lualatex --template=pandoc-template.lualatex.tex -o out.pdf hoge.md
```
