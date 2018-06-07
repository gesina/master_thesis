# Master Thesis on "Immersions and Stiefel-Whitney classes of Manifolds"
This is the source code of my Master thesis in mathematics
with the topic "Immersions and Stiefel-Whitney classes of Manifolds"
at the University of Regensburg,
supervised by Dr. Georgios Raptis.


## Structure
- `thesis.tex`: Main file for compilation
- `thesis-def.tex`: Definitions, package includes
- `thesis.bib`: Bibliography


## Compilation
(Tested) preliminaries: TeXLive 2018 distribution

The code uses `lualatex` and `bibtex` with `biber` backend.
For compilation execute the following commands
```bash
lualatex thesis.tex
biber thesis
lualatex thesis.tex
```
