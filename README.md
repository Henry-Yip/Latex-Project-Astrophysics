# Overleaf

Overleaf is an online, collaborative [LaTeX](https://en.wikipedia.org/wiki/LaTeX) Editor. 

## Downloading the documents

Go to [the offical website of Overleaf](https://www.overleaf.com/) and register for a new account. Create a new project and copy all the lines. Press compile and download the pdf document.

## Alternative-TexMaker

Download [TexMaker](https://www.xm1math.net/texmaker/) (Alternatively, you can also use [VSCode](https://code.visualstudio.com/Download), it looks better but they are essentially the same, excepts that VSCode also supports other programming languages, like Python, etc). There are tons of tutorials in youtube, make sure to check them out.

## Converting your PDF File in TexMaker to PDF
Download MikTeX (The Source Code is available in [GitHub](https://github.com/MiKTeX/miktex/)) and cd to the place you stored your tex file. 
```bash
pdflatex (name of your document).tex
```
You can also click "View" in TexMaker, then "print" and then "Microsoft Print to Pdf". However, for me, the hyperlink doesn't work if I use this method (I will investigate on that)

