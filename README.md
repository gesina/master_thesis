# Master Thesis on "Immersions and Stiefel-Whitney classes of Manifolds"
This is the source code, PDF, and other handed-in material of my
Master thesis in mathematics with the topic 
"Immersions and Stiefel-Whitney classes of Manifolds" 
at the University of Regensburg, supervised by Dr. Georgios Raptis,
and handed in on October 4, 2018.
Please find the abstract within `thesis.pdf`.


## Structure
- `Immersions_and_Stiefel-Whitney_Classes_of_Manifolds.pdf`: handed-in PDF version
- `thesis.tex`: Main file for compilation
- `thesis-def.tex`: Definitions, package includes
- `thesis.bib`: Bibliography
- `thesis-abstract.tex`, `thesis-0*.tex`: Abstract and chapter content files
- `thesis-cd*`: Stuff for handed-in CD with PDF


## Compilation
(Tested) preliminaries: TeXLive 2018 distribution

The code uses `lualatex` and `bibtex` with `biber` backend.
For compilation of the thesis execute the following commands
```bash
lualatex thesis.tex
biber thesis
lualatex thesis.tex
```
respectively
```bash
lualatex thesis-cd-cover.tex
```
for the CD-cover.
