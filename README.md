# Awesome LaTeX [![awesome]](https://github.com/sindresorhus/awesome) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat)](LICENSE.md)

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png" align="right" width="100">](https://www.latex-project.org/)

> This is a curated list of awesome stuff for the [(La)TeX typesetting system](https://www.latex-project.org/).

## Contents

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Learning LaTeX](#learning-latex)
- [Distributions](#distributions)
- [Engines](#engines)
	- [LaTeX formulas on the web](#latex-formulas-on-the-web)
- [Editors](#editors)
	- [LaTeX-focused](#latex-focused)
	- [General purpose text editors](#general-purpose-text-editors)
	- [Online editors](#online-editors)
- [Bibliography tools](#bibliography-tools)
- [Build Tools](#build-tools)
- [Misc. Tools](#misc-tools)
- [LaTeX-compatible GUI tools](#latex-compatible-gui-tools)
- [Packages](#packages)
	- [References](#references)
	- [Tables](#tables)
	- [Graphics](#graphics)
		- [PSTricks](#pstricks)
		- [TikZ](#tikz)
	- [Source Code](#source-code)
	- [Typography](#typography)
- [Templates](#templates)
- [Symbols](#symbols)
- [Resources](#resources)
- [Showcases](#showcases)
- [Tutorials](#tutorials)
- [Books](#books)
- [Blogs](#blogs)
- [Social media](#social-media)
- [Meta Awesome-LaTeX](#meta-awesome-latex)
- [Legend](#legend)

<!-- /TOC -->

## Learning LaTeX

Guides how to learn LaTeX

- [learnlatex.GitHub.io](https://learnlatex.GitHub.io/) - Browser-based LaTeX tutorial.

## Distributions

- [MacTeX](https://tug.org/mactex/) - Most common LaTeX distribution for macOS, basically TeXLive with some Mac-specific tools added. ![mac]
- [TeX Live](https://www.tug.org/texlive/) - Most common LaTeX distribution for Unix-like operating systems, including GNU/Linux. Also works on Windows. ![linux] ![windows]
- [MikTeX](https://miktex.org) - Most common LaTeX distribution for Windows, but also available for Mac, Linux or as Docker image. ![foss]

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/) - TeX compiler that produces PDF files immediately instead of DVI files (nowadays, this is the standard compiler for many users). ![foss]
- [XeTeX](http://xetex.sourceforge.net) - TeX compiler that provides better unicode and font support than TeX/pdfTeX (i.e. you can use the  fonts of your operating system instead of only TeX fonts). ![foss]
- [LuaTeX](http://www.luatex.org) - (La)TeX compiler that supports Lua code for scripting and has improved unicode and font support than standard TeX/pdfTeX. ![foss]
- [tectonic](https://tectonic-typesetting.GitHub.io/en-US/) - Modern, self contained (La)TeX compiler powered by XeTeX and TeXLive. ![foss]

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - Render high-quality math equations directly in Google Docs.
- [MathJaX](https://www.mathjax.org) - JavaScript engine to render mathematical formulas on the web. The outcome looks really slick. ![foss]
- [mimeTeX](https://ctan.org/pkg/mimetex) - mimeTeX is a rather old tool to render LaTeX formulas to PNG figures for your web site, without actually needing a LaTeX installation on your server. ![foss]
- [mathTeX](https://ctan.org/pkg/mathtex) - mathTeX is the successor of mimeTeX: it produces nicer-looking images but it requires LaTeX to be installed on your server. ![foss]
- [KaTeX](https://khan.GitHub.io/KaTeX/) - KaTeX is a math rendering library made by Khan Academy focusing on fast load times. All output is processed as plain HTML instead of fixed images. ![foss]
- [Franklin.jl](https://franklinjl.org/) - Static site generator with KaTeX support, code evaluation, LaTeX-like commands and optional pre-rendering, in Julia. ![foss]
- [Purple Pi](https://github.com/nschloe/purple-pi) - Browser extension that lets you use LaTeX in GitHub pages, StackOverflow etc. ![foss]

## Editors

Because editing LaTeX code with notepad is not awesome.
There are many editors out there, below are the most awesome editors.
A complete list of LaTeX editors is collected at [tex.stackexchange.com](https://tex.stackexchange.com/) as [big list of LaTeX Editors/IDEs](https://tex.stackexchange.com/q/339/9075).

- [List of popular LaTeX editors](https://tex.stackexchange.com/questions/339/latex-editors-ides) - Community-maintained list of popular LaTeX editors including a screenshot and a short description.

### LaTeX-focused

Some of the most awesome editor for LaTeX do just that: edit LaTeX.

- [Kile](https://kile.sourceforge.io) - Great LaTeX editor originally from the Linux/KDE community. It runs fine on Windows and macOS as well. ![foss]
- [TeXMaker](http://www.xm1math.net/texmaker/) - Pretty good alternative to Kile.
- [TeXStudio](https://www.texstudio.org) - Cross-platform LaTeX editor that stems from TeXMaker.
- [WinEdt](http://www.winedt.com) - The LaTeX editor many people swear by. Only for ![windows].
- [TeXnicCenter](http://www.texniccenter.org) - Quite old but free and decent editor for LaTeX. ![windows]
- [LyX](https://www.lyx.org) - Cross-platform WYSIWYM editor that uses LaTeX behind the scenes to render documents. ![foss]
- [TeXShop](http://pages.uoregon.edu/koch/texshop/) - No-nonsense editor for LaTeX documents which is included in MacTeX. ![mac]
- [TeXWorks](https://www.tug.org/texworks/) - No-nonsense editor for LaTeX code, modeled after TeXShop, but this one is cross-platform. ![foss]
- [BakomaTex](http://www.bakoma-tex.com) - Commercial LaTeX editor that allows to edit your document both using its source code and WYSIWYG.
- [Inlage](http://www.inlage.com/home) - Commercial LaTeX editor with handwritten formula recognition, Excel importing and more nifty features. ![windows]
- [Texpad](https://www.texpadapp.com) - Commercial LaTeX editor for macOS and iOS, with excellent features (document overview, synchronised PDF display, autocompletion, sync across devices, etc.) that never get in the way of writing. ![mac]

### General purpose text editors

These editors are no one-trick ponies: sure, they edit LaTeX, but they can do a lot more!

- [Atom](https://atom.io) [![Atom][awesome]](https://github.com/mehcode/awesome-atom) ![foss]
	- [LaTeXTools](https://atom.io/packages/latextools) - Atom port of the Sublime Text package of the same name. ![foss]

- [Sublime Text](https://www.sublimetext.com) [![Sublime Text][awesome]](https://github.com/dreikanter/sublime-bookmarks)
	- [LaTeXing](http://www.latexing.com) - Commercial plug-in to edit LaTeX.
	- [LaTeXTools](https://github.com/SublimeText/LaTeXTools) - Free LaTeX plugin for Sublime Text. ![foss]

- [Emacs](https://www.gnu.org/software/emacs/)  [![Emacs][awesome]](https://github.com/emacs-tw/awesome-emacs) ![foss]
	- [AucTeX](https://www.gnu.org/software/auctex/) - Emacs plugin for LaTeX that also shows a preview of equations and figures. ![foss]
	- [RefTeX](https://www.gnu.org/software/auctex/reftex) - Emacs plugin for LaTeX that adds support for labels, references, and citations. ![foss]

- [Vim](http://www.vim.org) [![Vim][awesome]](https://github.com/mhinz/vim-galore) ![foss]
	- [Vim-LaTeX](http://vim-latex.sourceforge.net) ![foss]
	- [LaTeX Live Preview](https://github.com/xuhdev/vim-latex-live-preview) - Instantly previews your LaTeX document. ![foss]
	- [vimtex](https://github.com/lervag/vimtex) - Modern vim plugin for editing LaTeX files. Has a variety of features including live preview and forward search. ![foss]

- [IntelliJ](https://www.jetbrains.com/idea/)
	- [TeXiFy-IDEA](https://github.com/Ruben-Sten/TeXiFy-IDEA) - Free LaTeX plugin for IntelliJ IDEA. ![foss]

- [VS Code](https://code.visualstudio.com/) [![VS Code][awesome]](https://github.com/viatsko/awesome-vscode) ![foss]
	- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) - LaTeX extension for Visual Studio Code ![foss]

### Online editors

Online editors that allow you to edit documents collaboratively.

- [List of popular online LaTeX editors](https://tex.stackexchange.com/questions/3/compiling-documents-online/1654#1654) - Community-maintained list of popular online LaTeX editor including equation editors.
- [Authorea](https://www.authorea.com) - Online editor with built-in git support and bibliography tools.
- [ShareLaTeX](https://www.sharelatex.com) - Has pretty great LaTeX documentation and simple version control.
- [Overleaf](https://www.overleaf.com) - Online editor, also with a WYSIWYM editor and git support.
- [Papeeria](https://papeeria.com) - Online editor with built-in git support.
- [JaxEdit](https://zohooo.GitHub.io/jaxedit/) - Online LaTeX editor with Live Preview and nice presentation mode.

## Bibliography tools

- [JabRef](https://www.jabref.org) - Very powerful cross-platform (Java) bibtex editor. The GUI looks quite dated, though. ![mac] ![windows] ![linux] ![foss]
- [Papis](https://github.com/alejandrogallo/papis) - Extremely customizable,
  powerful and simple cross-platform (Python) library manager. It has a very
  complete Command-Line-Interface, several GUIs and scripting capability.
  ![linux] ![mac] ![foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - Great bibliography editor for ![mac].
- [Zotero](https://www.zotero.org) - Reference manager for your browser that also exports to bibtex and integrates with many LaTeX editors. ![mac] ![windows] ![linux] [![foss]](https://github.com/zotero/)
- [Mendeley](https://www.mendeley.com) - Both an app and cloud client to manage your references and PDFs. Can sync out to a bibtex file for your LaTeX workflow. ![mac] ![windows] ![linux]
- [betterbib](https://github.com/nschloe/betterbib) - Command-line utility for improving your BibTeX files. Fetches information from online sources. ![mac] ![windows] ![linux] ![foss]

## Build Tools

Compiling LaTeX documents can be tedious, build tools help you to manage the compilation process.

- [Arara](https://www.ctan.org/pkg/arara) ([GitHub repo](https://github.com/cereda/arara)) - Simple tool that allows you to specify which tools to call inside your document and it can be extended quite easily. ![foss]
- [latexmk](https://www.ctan.org/pkg/latexmk) - Build tool that is the commonly used by many LaTeX editors (LaTeXing, TeXShop, etc.) to build your LaTeX files. ![foss]
- [latex-makefile](https://github.com/alejandrogallo/latex-makefile) - `Makefile` based build tool that attempts to be as general and lightweight as possible. ![foss]

## Misc. Tools

- [CaTeX](https://github.com/Alexis-benoist/CaTeX) - Concatenates LaTeX documents with attention for properly merging the preamble.
- [Pandoc](https://pandoc.org) - This program converts almost any document format (LaTeX, DOC, markdown, etc.) to almost any other format. A great tool to aid workflows where multiple formats are used. ![foss]
- [Codecogs Eqn Editor](https://www.codecogs.com/latex/eqneditor.php) - Online LaTeX equation editor that allows you to produce figures containing an equation.
- [LaTeXiT](https://www.chachatelier.fr/latexit/) - LaTeXit is an equation editor that makes it easy to drag-and-drop rendered equations (as PDF, PNG, etc.) into your non-LaTeX documents on the Mac. ![mac]
- [KLaTeXFormula](https://klatexformula.sourceforge.io) - Cross-platform alternative for LaTeXit. ![foss]
- [EqualX](http://equalx.sourceforge.net) - Graphical LaTeX formula editor. ![windows] ![linux] ![foss]
- [ChkTeX](http://baruch.ev-en.org/proj/chktex/) - Linter / code checker for LaTeX documents. ![foss]
- [LaTeXEqEdit](http://latexeqedit.sourceforge.net/index.php) - LaTeX formula editor for Windows. ![windows] ![foss]
- [Laeqed](https://www.thrysoee.dk/laeqed/) - Crossplatform LaTeX formula to PNG convertor. ![windows] ![linux] ![mac] ![foss]
- [blacktex](https://github.com/nschloe/blacktex) - Command-line tool that replaces commonly occurring LaTeX anti-patterns and cleans up your files. ![windows] ![linux] ![mac] ![foss]

## LaTeX-compatible GUI tools

- [TikzEdt](http://www.tikzedt.org) (also: [GitHub repo](https://github.com/hchapman/tikzedt)) - WYSIWYG and text-based editor for TikZ pictures. ![foss]
- [TikZ-Editor](https://github.com/fredokun/TikZ-Editor) - Live-previewing editor for TikZ figures. ![mac] ![linux] ![foss]
- [IPE](http://ipe.otfried.org) - Drawing tool that integrates well with LaTeX commands and documents. ![foss]
- [GeoGebra](https://www.geogebra.org/cms/) - Cross-platform geometry tool with output to TikZ. ![foss]
- [Dia](https://wiki.gnome.org/Apps/Dia) - Cross-platform diagramming tool that can export to PSTricks and MetaPost code. ![foss]
- [TikZiT](https://tikzit.GitHub.io) - GUI tool for creating graphs and string diagrams using PGF/TikZ. ![windows] ![linux] ![mac] ![foss]


## Packages

- [CTAN](https://www.ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

### References

- [Cross-reference packages explained](https://tex.stackexchange.com/a/36312/9075) - Elaboration on cross-reference packages (cleveref, varioref, theoremref, nameref, etc.): Which to use, which conflict?

### Tables

- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex?lang=en) - Excel (2010 and older) macros to produce LaTeX `tabular` code. ![windows] ![mac]
- [csv2latex](http://freshmeat.sourceforge.net/projects/csv2latex) - Converts CSV files from your favorite programs to LaTeX `tabular`s. ![linux] ![mac]
- [Tables Generator](https://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, etc.
- [pgfplotstable](https://www.ctan.org/pkg/pgfplotstable?lang=en) - This package displays numerical tables rounded to desired precision in various display formats. It can even read CSV files to include directly in your LaTeX document.

### Graphics

#### PSTricks

PSTricks is a great library to draw figures for inclusion in PostScript/DVI files.

#### TikZ

TikZ is an awesome package with many plugins that allow you to create figures from within your LaTeX documents.
Typically, it is easier to get to work with `pdflatex` than PSTricks is.

- [TeXample](http://www.texample.net) - Blog about LaTeX, with a big collection of TikZ figures.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-) - Useful website with some custom packages to draw special plots (Bode, Nyquist, electrical schematics, block schematics, etc.) using TikZ. Note that everything is in French.
- [tkz](http://altermundus.com/pages/tkz/index.html) - Collection of TikZ-based packages to make plots and graphs.
- [pgfplots](http://pgfplots.sourceforge.net) - Truly awesome plotting library on top of and in the style of TikZ/pgf. This library can load in CSV data files, perform some calculations and create beautiful plots.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - Short introductory document to the world of TikZ, written by Jacques Crémer.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - Collection of publication-ready PGF/TikZ figures by Petar Veličković.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz) - Convert your MATLAB plots to PGFPlots/TikZ. ![windows] ![linux] ![mac] ![foss]
- [tikzplotlib](https://github.com/nschloe/tikzplotlib) - Convert your matplotlib plots to PGFPlots/TikZ. ![windows] ![linux] ![mac] ![foss]
- [TikZBlog](https://latexdraw.com) - Step-by-Step Tutorials about How to Draw Illustrations in LaTeX.

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - The minted package uses [pygments](http://pygments.org/) to generate the listings. In this way, LaTeX is able to format more than 300 programming and markup languages and other text formats.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - This package improves the appearance of your documents by enabling margin kerning and font expansion.

### Presentations, Slides

- [nics](https://nics.nilcons.com/) - An opinionated alternative to Beamer, that we created with the hopes to make common tasks very easy and beautifully rendered by default.  Has awesome documentation and a detailed cheatsheet to help you getting started.

## Templates

- [LaTeX templates](https://www.latextemplates.com) - Collection of templates for papers, posters, resumés, theses, books, presentations, … for LaTeX.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - Links to various beamer themes along with PDF previews.

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/) - Very extensive list of symbols for LaTeX. Available in [A4](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) and [letter](http://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) sizes.
- [Detexify](http://detexify.kirelabs.org/classify.html) - You draw the symbol and this site/app will tell you the LaTeX command.

## Resources

- [TUG](https://www.tug.org) - The TeX User Group is a way to get in touch with other (La)TeX users.
- [TeXDoc](http://texdoc.net) - Online interface to the `texdoc` utility to browse LaTeX packages and documentation.
- [Dickimaw Books: LaTeX resources](http://www.dickimaw-books.com/latexresources.html) - Great overview of resources useful for LaTeX.
- [LaTeX cookbook](http://latex-cookbook.net) - Sibling of TeXample, contains quite a bit of example code.
- [Visual FAQ](http://mirrors.ctan.org/info/visualFAQ/visualFAQ.pdf) - Typesetting issues and a link to appropriate TeX FAQ answers.
- [MartinThoma's LaTeX example](https://github.com/MartinThoma/LaTeX-examples/) - GitHub repository containing example LaTeX documents.
- [MacTeX Wiki: TeX Extras](http://mactex-wiki.tug.org/wiki/index.php/TeX_Extras) - Overview of useful tools for LaTeX. Many of them are specific for Mac, but quite a bit are useful for other platforms as well.
- [LaTeX community](http://latex.org/index.php) - Forum and blog about LaTeX.
- German: [Neue TeX FAQ](https://texfragen.de) - Modern and updated LaTeX FAQ in German.
- [BibTeX Style Examples](http://www.cs.stir.ac.uk/~kjt/software/latex/showbst.html) - Example output of common BibTeX styles (BST files).
- [TeX World](http://tex.world/) -  Websites supported by the TeX Users Group, DANTE, and GUTenberg.
- [TeXnique](https://texnique.xyz) - A LaTeX Typesetting Game.

## Showcases

- [Showcase of beautiful typography done in TeX & friends](https://tex.stackexchange.com/questions/1319/showcase-of-beautiful-typography-done-in-tex-friends) - Set of examples demonstrating the power of LaTeX.
- [Showcase of beautiful invitations in TeX](https://tex.stackexchange.com/q/281415/9075) - Showcase of invitations typeset using LaTeX.
- [Showcase of "programming your document" paradigm](https://tex.stackexchange.com/q/219774/9075) - Collection of LaTeX documents demonstrating how LaTeX can be used like a programming language.
- [TUG: TeX showcase](https://www.tug.org/texshowcase/) - Website from the TUG that shows some examples of what LaTeX can do.

## Tutorials

- [The (Not So) Short Introduction to LaTeX2e](http://mirrors.ctan.org/info/lshort/english/lshort.pdf) - Very comprehensive introduction to LaTeX.
- [Begin LaTeX in minutes](https://github.com/LewisVo/Begin-Latex-in-minutes) - Brief intro to LaTeX for beginners that helps you use LaTeX with ease.
- [Getting to Grips with LaTeX](https://www.andy-roberts.net/writing/latex) - Complete guide going through the majority of things you need to know about LaTeX.
- [LaTeX introductions in languages other than English](https://tex.stackexchange.com/questions/84384/latex-introductions-in-languages-other-than-english/84385) - Collection of introductions in many languages.

## Books

- [Wikibooks: LaTeX](https://en.wikibooks.org/wiki/LaTeX) - The LaTeX wikibook. Not really a paper book, but it is equally extensive.
- [The LaTeX Companion, F. Mittelbach (2004)](https://www.informit.com/store/latex-companion-9780201362992)
- [LaTeX Graphics Companion, M. Goossens (2007)](https://www.informit.com/store/latex-graphics-companion-9780321508928)
- [TeX by Topic (2007)](https://ctan.org/pkg/texbytopic)
- [TeX for the Impatient (2020)](https://ctan.org/pkg/impatient)
- [Formatting Information (2020)](http://latex.silmaril.ie/formattinginformation) - This is the HTML5-based online version of the book *Formatting Information - An introduction to typesetting with LATEX*. It has been continuosuly updated since the early 2000s.

## Blogs

- [TeXblog](http://texblog.net) - Blog about LaTeX and everything related.
- [texblog.org](https://texblog.org) - Blog on LaTeX and related topics (tutorials, packages, code snippets, etc.).
- [TeX Talk](http://tex-talk.net) - Blog for the TeX Stack Exchange site with news and interviews.

## Social media

- [LinkedIn: TeX/LaTeX User Group](https://www.linkedin.com/groups/1600297)
- [Twitter: @TeXtip](https://twitter.com/TeXtip) - Tips related to (La)TeX by [John D. Cook](https://www.johndcook.com/).
- [TeX.StackExchange](https://tex.stackexchange.com) - StackExchange TeX section.

---

<!-- Icons -->

## Meta Awesome-LaTeX

If you want to contribute, please do read our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

## Legend

The icons indicating Mac, Linux and Windows compatibility show when a program is *only* available for those platforms. So absence of those icons means that the software is fully cross-platform.

|       Logo          | Description                                   |
|:-------------------:|:----------------------------------------------|
| ![mac]         | [macOS](https://www.apple.com/osx/)                |
| ![linux]     | [GNU/Linux](https://www.gnu.org)                     |
| ![windows] | [Microsoft Windows](https://www.microsoft.com/windows) |
| ![FOSS]       | [Free Open-Source Software](https://opensource.org) |

---

All trademarks are property of their respective owners.

[mac]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/apple.svg
[linux]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/linux.svg
[windows]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/windows.svg
[foss]: https://cdn.rawgit.com/egeerardyn/awesome-LaTeX/700138fe725574e1741f148df6d1f77a8aa07eee/fig/foss.svg
[awesome]:  https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
