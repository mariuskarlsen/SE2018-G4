# SE18-G6
[![GitHub commits](https://img.shields.io/badge/Tex%20Live-2017-yellowgreen.svg)](tug.org/texlive/)

### Installation (TeX Live)
This documentation is developed in `LaTeX`, and to be able to compile it, you need the latest version of a TeX distribution. Please visit [TeXLive](tug.org/texlive/) and follow the instructions. ([MacTeX](tug.org/mactex/) for macOS)

We recommend TeX Live, as it is the most straigth forward one to use.
Make sure you are using the latest updates by running the following command after installation:

`tlmgr update --all`

### Usage
To compile the source, you will need to use `XeTeX`, `LuaTeX` or  `PdfTex` typesetting engine. The normal engine will fail to compile.

in a shell or on the windows commandline, run the following command:

`/path/to/repo/xelatex main.tex`

Or use your favourite TeX editor, we use [Atom](github.com/atom/atom/releases/tag/v1.16.0) with [LaTeX](atom.io/packages/latex), [Language-LaTeX](atom.io/packages/language-latex) and [LaTeX-autocomplete](atom.io/packages/latex-autocomplete) packages installed.

Other options are plenty, such as [TeX Studio](texstudio.sourceforge.net/) or check out [this page](http://alternativeto.net/software/latex/) for other alternatives (scroll down on the page).