# Introduction
This set of notes is made with reference to the **Astrophysics Coursebook** by **The University of Edinburgh**. I have gained permission from Professor **Catherine Heymans** to put my modified notes in my website, and I think this refers to GitHub also. It is also available in my personal website.

## Prerequisites
Proficiency in Calculus and Classical Physics, in particular, Newtonian Mechanics.

## Scope
Galaxies and Cosmology, with some coverage on stars. 

# Download
There are 2 suggested ways to download the pdf. 

# 1. Overleaf

Overleaf is an online, collaborative [LaTeX](https://en.wikipedia.org/wiki/LaTeX) Editor. 

## Downloading the documents

Go to [the offical website of Overleaf](https://www.overleaf.com/) and register for a new account. Create a new project and copy all the lines in main.tex (the document above). Press compile and download the pdf document.

# 2. TexMaker

Download [TexMaker](https://www.xm1math.net/texmaker/) (Alternatively, you can also use [VSCode](https://code.visualstudio.com/Download), it looks better but they are essentially the same, excepts that VSCode also supports other programming languages, like Python, etc)

## Converting your PDF File in TexMaker to PDF
Save your document as Astrophysics.tex. Download MikTeX (The Source Code is available in [GitHub](https://github.com/MiKTeX/miktex/)), go to comamnd prompt and cd to the place you stored your tex file. 
```bash
pdflatex Astrophysics.tex
```
You can also click "View" in TexMaker, then "print" and then "Microsoft Print to Pdf". However, at least for me, the hyperlinks may be lost.
