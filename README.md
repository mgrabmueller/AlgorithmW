# AlgorithmW

Example implementation of Algorithm W for Hindley-Milner type inference.

# The PDF

The PDF version of the tutorial is in subdirectory `pdf`.

# Playing with the code

You can load the code into ghci and play with it like this:

```
ghci AlgorithmW.lhs
```

# How to build

On Debian 10, the following should work and create Transformers.pdf:

```
sudo apt install texlive

lhs2TeX AlgorithmW.lhs > AlgorithmW.tex
pdflatex AlgorithmW.tex
bibtex AlgorithmW.aux
pdflatex AlgorithmW.tex
mv AlgorithmW.pdf pdf/
```

