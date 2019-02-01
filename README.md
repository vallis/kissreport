# Final report from the KISS study on the Architecture of the LISA Science Analysis.

It's [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), so you can edit semi-visually with many modern editors. Why Markdown? So I can easily make a website out of this, in addition to a printable document.

You'll figure out the bibliography easily; mostly I've used the DOI as the key, then pulled the BibTeX off ADS. Then the citation is just `[@citekey]`.

If you want to build the PDF, do

    pandoc KISS.md -t latex -s --template tufte-handout.tex --variable documentclass="tufte-book" --top-level-division=chapter --bibliography=bib.bib --csl=chicago-fullnote-bibliography.csl -o KISS.pdf

after installing `pandoc`, `pandoc-citeproc`, and of course LaTeX. (On OS X, [Homebrew](https://brew.sh) has everything.) Since you may not want to bother, I will periodically commit the built PDF also.
