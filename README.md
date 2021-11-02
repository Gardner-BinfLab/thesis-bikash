# PhD-thesis
LaTeX files for my PhD Thesis. The compiled PDF can be viewed [here](https://raw.githubusercontent.com/Gardner-BinfLab/thesis-bikash/master/main.pdf).


### Compilation
I used TeXstudio on Ubuntu 18.04.5 to compile this.
These are the configurations that work.
 - Configure > Build > Build & View
     `txs:///pdflatex | txs:///biber | txs:///pdflatex | txs:///pdflatex`
 - Configure > Build > Default Bibliography Tool
     `Biber`
 - Bibliography > Type 
     `BibLaTeX`
 - `sudo apt-get install texlive-fonts-extra` for extra fonts. Else comment out these lines in `preamble/packages.tex`:
      ```sh
      \usepackage{gfsartemisia-euler}
      \usepackage[T1]{fontenc}
      ```

