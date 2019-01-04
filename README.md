# A HSG LaTeX Template

A LaTeX template for humans at HSG.

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

TeXStudio: https://www.texstudio.org

**windows**\
TeXniCe: http://www.texniccenter.org

TeXStudio: https://www.texstudio.org

With the right plugins, you can also use [Atom](https://atom.io).
![Atom](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/atom01.png) (this is the editor we mostly use)

For example, using combination of the two packages:

- [language-latex](https://atom.io/packages/language-latex)
- [latextools](https://atom.io/packages/latextools)

![Atom](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/atom02-packages.png)

### Get template

[Download](https://github.com/severinlandolt/hsg-latex-template/archive/master.zip) or Clone this Git Repository

```
git clone <url_of_repository>
```

Open the folder in your favourite TeX editor. If you have any problems with "rendering" your PDF, just delete the .aux file.

## Citation

We are using the _natbib_ package to cite in the prose text and also to generate the bibliography. Here we will explain the workflow of citing. The template is set up to APA-Style referencing.

**Prepare your bibliographic database**\
Copy/Paste the source you want to cite in a BibTeX formatting (see screenshot below) into your references.bib file. Bear in mind that LaTeX by default only puts those sources into the final references section which are actually cited in the document.
![references01](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/references01.png)



**Ways to cite**\
There are plenty ways to cite. The following information is mostly derived from [natbib's documentation](https://ctan.org/pkg/natbib?lang=de). Basically there are two basic citation commands, \citet and \citep for textual and parenthetical citations. There exist also starred versions \citet* and \citep* that print the full author list, and not just the abbreviated one.<br>

![finalref](https://raw.githubusercontent.com/severinlandolt/hsg-latex-template/master/images/finalref3.png)

## Further reading

[A great LaTeX Cheatsheet](https://wch.github.io/latexsheet/)\
[Tobi Oetiker's *The not so Short Introduction to LaTeX2e*](https://tobi.oetiker.ch/lshort/lshort.pdf)

## Authors

* [Severin Landolt](https://github.com/severinlandolt)
* [Tetyana Drobot](https://github.com/deltani)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/severinlandolt/hsg-latex-template/blob/master/LICENSE) file for details
