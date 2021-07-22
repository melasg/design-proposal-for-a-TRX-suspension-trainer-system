# design-project-TRX-system
 Design of aPortable TRX Suspension Trainer Anchoring Structure for a mechanical engineering course.
## Structure
```
.
├── README.md
├── src/
│   ├── coverpage.tex
│   ├── contents.tex
|   ├── introduction.tex
|   ├── chap2.tex (Problem Definition)
|   ├── chap3.tex (Solution Procedure)
|   ├── chap4.tex (Conceptual Designs)
|   ├── chap5.tex (Analysis of the Proposed Designs)
|   ├── chap6.tex (Concept Selection)
|   ├── chap7.tex (Conclusions)
|   ├── chap8.tex (Recommendations)
|   ├── appa.tex (Appendix A - Units/Tables/Formulas)
│   └── refs.bib (works cited)
├── Figures/
│   ├── imags
│   └── static
└──Makefile
```
## Compile instructions
1. `latex main.tex` -> check for errors
2. `make clean; make`
3. open `main.ps`