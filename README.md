# BGP Tracer - Research Paper

LaTeX source for the BGP Tracer research paper.

## Structure

- `main.tex` - Main document
- `section*.tex` - Paper sections
- `refs.bib` - Bibliography
- `figs/` - Figures

## Build

Compile with `pdflatex` + `biber`:

```bash
pdflatex main
biber main
pdflatex main
pdflatex main
```
