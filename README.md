# LaTeX Template for MMT degree programme

This template can be used for the seminar paper, bachelor thesis and
the master Thesis.

## Class options

To switch between templates go to the top of main.tex and change the document class options:

* `paper` =  seminar paper
* `reviewversion` = anonymized review version
* `bachelorthesis` = bachelor thesis
* `masterthesis` = master thesis

To switch the language of the document go to the top of main.tex and change the document class options: 

* `english`
* `ngerman`

## Template usage

The document adapts text of the title page, affidavit and references according to the language chosen.

Files to change for your paper:

* `_configuration.tex`: configuration file of the project (author name, advisor name, etc.)
* `body.tex`: the main text of the thesis
* `kurzfassung.tex`: the German abstract

for bachelor and master thesis also edit:

* `abstract.tex`: the English abstract
* `appendix.tex`: the optional appendix

only if you want to use advanced LaTeX features:

* `main.tex`: set up document class and add any packages you may need. The rest should be left untouched.

## PDF compilation

To compile the thesis, use the following command `latexmk -pdf -shell-escape main.tex`.
