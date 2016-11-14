# umons-latex-memoire-template

LaTeX template for UMons master thesis. 

To generate the PDF, use
```
make
```

The generated PDF file is available in the directory `_build` with the name `memoire.pdf`.

You can change the output directory by changing the variable `BUILD_DIRECTORY` in the makefile configuration `Makefile.config`.

If you use `bibtex` to generate the bibliography (which is recommended), add you `bib` file in the `src` directory and change the variable `USE_BIB` in the makefile configuration `Makefile.config` to `true`.
