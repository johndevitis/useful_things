---Pandoc---

# basics

pandoc pandoc acts as a filter in cmd


# example commands

pandoc master.md -s -o master.docx

pandoc -N --template=template1.tex --variable mainfont="Palatino" --variable sansfont="Century Gothic" --variable monofont="Consolas" --variable fontsize=12pt --variable version=1.15.2 master.md --latex-engine=xelatex --toc -o master.pdf


# for output to a file use the ```-o``` option

implicit_figures # for inline image rendering
--blank_before_header