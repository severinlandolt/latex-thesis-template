# A HSG LaTeX Template

A LaTeX template for humans at HSG.

There are two ways of getting started: 
1. Online Latex editor: Overleaf. For this download either little-prince-template or chinchilab-template, create zip file and import it to Overleaf. 

2. On your local machine. Please, follow a guide below: 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine to start writing your thesis.

### Prerequisites
The first part of a working LaTeX environment is a TeX distribution. This depends on your operating system. And yes, the file is big.  

**macOS:**
http://www.tug.org/mactex/

**windows:**
https://miktex.org

### Installing an editor

There are many capable text editors where you can code LaTeX.

**macOS**\
TextMate: https://macromates.com

texpad: https://www.texpad.com/osx (worth every penny!)

**windows**\
TeXniCe: http://www.texniccenter.org

With the right plugins, you can also use [Atom](https://atom.io).
![Atom](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/atom01.png) (this is the editor we mostly use)

For example, I use a combination of two packages:

- [atom-latex](https://atom.io/packages/atom-latex)
- [latex](https://atom.io/packages/latex)

![Atom](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/atom-packages.png)

### Get template

[Download](https://github.com/severinlandolt/hsg-latex-template/archive/master.zip) or Clone this Git Repository

```
git clone <url_of_repository>
```

In Atom, you first have to set a "root" file. A LaTeX root file is essential for Atom-LaTeX. Building, preview, autocompletion, and more features rely on its proper configuration. You can manually select the root file by clicking the `home` icon at the bottom of the editor. Select the *your_thesis.tex* file. This is the correct root file with the sequence `\begin{document}` in it.

If you have any problems with "rendering" your PDF, just delete the .aux file.

## Citation

We are using the _natbib_ package to cite in the prose text and also to generate the bibliography. Here we will explain the workflow of citing. The template is set up to APA-Style referencing.

**Prepare your bibliographic database**\
Copy/Paste the source you want to cite in a BibTeX formatting (see screenshot below) into your references.bib file. Bear in mind that LaTeX by default only puts those sources into the final references section which are actually cited in the document.
![references01](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/references01.png)

**Ways to cite**\
There are plenty ways to cite. The following information is mostly derived from [natbib's documentation](https://ctan.org/pkg/natbib?lang=de). Basically there are two basic citation commands, \citet and \citep for textual and parenthetical citations. There exist also starred versions \citet* and \citep* that print the full author list, and not just the abbreviated one.<br>

![finalref](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/finalref3.png)

## Miscellaneous

If you want to use an other paragraph styling, you can do this within the _settings.tex_ file. You can tune both the indentation (\parindent, default 0px) and the space between the paragraphs (\parskip, default 1em)

![paragraph](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/paragraph.png)

To create entries for a glossary or a list of abbreviations use the `\newglossaryentry{label}{name={key}, description={value}}` command in the little-_/01_head/abbreviations.tex_ file. In text use: `\gls{label}`.


## Further reading

[A great LaTeX Cheatsheet](https://wch.github.io/latexsheet/)\
[Tobi Oetiker's *The not so Short Introduction to LaTeX2e*](https://tobi.oetiker.ch/lshort/lshort.pdf)

## Authors

* [Severin Landolt](https://github.com/severinlandolt)
* [Tetyana Drobot](https://github.com/deltani)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/severinlandolt/hsg-latex-template/blob/master/LICENSE) file for details
