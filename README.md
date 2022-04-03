# My PhD dissertation defense presentation

This is my dissertation defense presentation. Made with Beamer: written in
[orgmode](https://orgmode.org/ "OrgMode website") syntax and then exported to
`.tex` using the standard [Emacs](https://www.gnu.org/software/emacs/)
machinery.

The main source file is `bochkarev_pres.org`, but since it is exported to LaTeX,
I use a lot of the corresponding magic here:
  + `bochkarev_pres.org` is exported to `bochkarev_pres.tex`, which is in turn compiled with LaTeX to `bochkarev_pres.pdf`
  + The notation is kept separately in `notation_def.tex`, which I just `\input`
    then. (Mostly copied from the dissertation text.)
  + some figures are done with TikZ (also mostly copied from the dissertation text). I found it convenient to write and 'debug' them separately first, in `quick.tex` using `\documentclass{standalone}`, so that I wouldn't need to wait while the whole presentation is recompiled if I only edited one figure. Some other figures are made with [Inkscape](https://inkscape.org/).
  
There are many good resources on Beamer (e.g., [this one](http://web.mit.edu/rsi/www/pdfs/beamer-tutorial.pdf "Fun with Beamer (from MiT)")), not sure which one to recommend here.
