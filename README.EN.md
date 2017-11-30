ThesisIST
=========

LaTeX template for Doctoral / Phd Thesis at Instituto Superior Técnico (Universidade de Lisboa). This is not an official template. You're advised to verify at the office that it satisfies all the rules at the time you're submiting your thesis.

Last registed submission based on this template: July, 2017.

This template is a fork of the Master Thesis template available in
https://github.com/themiguelamador/ThesisIST/


Thesis in English
----------------

When the thesis is written in english, the main file tese.tex must have:

* version of the style file: \documentclass[defaultstyle,10pt,master,Helvetica]{01.thesis}

* version of the cover in english: \input{0.Inicio/1.cover_EN_draft.tex}

* apropriate selection of the language after %% Use Main document Language -> \selectlanguage{english}

You need to edit the [cover](https://github.com/FilipeMar/ThesisIST/blob/master/0.Inicio/1.cover_EN_draft.tex) and the personal info in the [main file](https://github.com/FilipeMar/ThesisIST/blob/master/tese.tex).

LaTeX Packages
--------------

[`00.Definitions/packages.tex`](https://github.com/FilipeMar/ThesisIST/blob/master/00.Definitions/packages.tex) contains the LaTeX packages used in the template.
You can edit the file to add the packages you need.

The file [`00.extra_functions.sty`](https://github.com/FilipeMar/ThesisIST/blob/master/00.extra_functions.sty) contains the definition of some custom commands.
You can edit it to add your own custom commands.

The files `00.listofsymbols.sty` e `00.symlist.sty` define more extra commands.

#### Figures, Floats, and Captions

* [Wiki LaTeX Floats,_Figures_and_Captions.](https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions)


#### Glossary / Notation / Acronyms

* [Wiki LaTeX Glossary.](https://en.wikibooks.org/wiki/LaTeX/Glossary)

#### Units

The file [`00.Definitions/packages.tex`](https://github.com/FilipeMar/ThesisIST/blob/master/00.Definitions/packages.tex) contains at its bottom, a section with the declaration of new units.
*Examples:*
`\DeclareSIUnit\Mtoe{\mega \tonne oe}`, use in text: `\SI{100}{\Mtoe}`

`\DeclareSIUnit\GWh{GWh}`, use in text: `\SI{100}{\GWh}`

For more information, please read the [package documentation](ftp://ftp.dante.de/ctan%3A/macros/latex/exptl/siunitx/siunitx.pdf).