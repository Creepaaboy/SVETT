# Datasektionens Nanobryggeris stadgar

LaTeX source for the statutes of Datasektionens Nanobryggeri.

## Build

Requires a LaTeX installation with `latexmk` and `pdflatex`.

```powershell
latexmk -pdf -jobname=stadgar main.tex
```

The PDF is written to `stadgar.pdf`. Replace the `202?-??-??` date placeholders
in `main.tex` and `preamble.tex` with the date the statutes are adopted.

## Structure

Each chapter is kept in its own file under `sections/`, in document order:

- `01-allmant.tex`: General provisions
- `02-medlemmar.tex`: Membership
- `03-organisation.tex`: Organization
- `04-medlemsmote.tex`: Member meetings
- `05-arsmote.tex`: Annual meetings
- `06-styrelsen.tex`: The board
- `07-val.tex`: Elections
- `08-stadgeandring.tex`: Amendments