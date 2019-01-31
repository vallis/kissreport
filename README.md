# kissreport
Final report from the KISS study on the Architecture of the LISA Science Analysis

Build with

    pandoc KISS.md -t latex -s --template tufte-handout.tex --variable documentclass="tufte-book" --top-level-division=chapter --bibliography=bib.bib --csl=chicago-fullnote-bibliography.csl -o KISS.pdf

after installing `pandoc`, `pandoc-citeproc`, and of course LaTeX. Since you may not want to bother, I will be periodically commit the PDF output also.
