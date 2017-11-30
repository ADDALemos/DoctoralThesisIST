ThesisIST
=========

Template de LaTex para Tese de Doutoramento no Instituto Superior Técnico. Este template não é oficial. Aconselha-se portanto a verificação da satisfação de todas as regras indicadas para a redacção deste trabalho académico no momento de entrega.

Último registo de submissão de tese baseada neste template: Julho de 2017.

Este template deriva do template para teses de mestrado disponível em
https://github.com/themiguelamador/ThesisIST/

*Read this in other languages*: [English](https://github.com/FilipeMar/ThesisIST/README.EN.md ).

Tese em Português
----------------

No caso de a tese ser escrita em português, o ficheiro principal tese.tex deve ter:

* versão do ficheiro de estilo em português: \documentclass[defaultstyle,10pt,master,Helvetica]{01.thesis_pt}

* versão da capa em português: \input{0.Inicio/1.cover_PT_draft.tex}

* selecção da linguagem após o %% Use Main document Language -> \selectlanguage{portuguese}

*No caso de ser escrita em inglês, ver a versão deste documento em* [English](https://github.com/FilipeMar/ThesisIST/blob/master/README.EN.md ).

Tens de editar a [capa](https://github.com/FilipeMar/ThesisIST/blob/master/0.Inicio/1.cover_PT_draft.tex) e adicionar a informação pessoal nos espaços respectivos no [main file](https://github.com/FilipeMar/ThesisIST/blob/master/tese.tex).

LaTeX Packages
--------------

O ficheiro [`00.Definitions/packages.tex`](https://github.com/FilipeMar/ThesisIST/blob/master/00.Definitions/packages.tex) contém os pacotes usados pelo template.
Podes edita-lo para acrescentar pacotes extra consoante as tuas necessidades.

O ficheiro [`00.extra_functions.sty`](https://github.com/FilipeMar/ThesisIST/blob/master/00.extra_functions.sty) contém a definição de alguns comandos extra personalizados.
Podes editá-lo para acrescentar os teus comandos personalizados.

Os ficheiros `00.listofsymbols.sty` e `00.symlist.sty` definem mais comandos extra.

#### Figures, Floats, and Captions

Ver [Wiki LaTeX Floats,_Figures_and_Captions.](https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions)


#### Glossário / Notação / Acrónimos

Ver [Wiki LaTeX Glossary.](https://en.wikibooks.org/wiki/LaTeX/Glossary)

#### Unidades

O ficheiro [`00.Definitions/packages.tex`](https://github.com/FilipeMar/ThesisIST/blob/master/00.Definitions/packages.tex) contém uma secção para a declaração de unidades novas no final do ficheiro.
*Exemplos:*
`\DeclareSIUnit\Mtoe{\mega \tonne oe}`, uso no texto: `\SI{100}{\Mtoe}`

`\DeclareSIUnit\GWh{GWh}`, uso no texto: `\SI{100}{\GWh}`

Para informação mais completa, ver a [documentação](ftp://ftp.dante.de/ctan%3A/macros/latex/exptl/siunitx/siunitx.pdf).


