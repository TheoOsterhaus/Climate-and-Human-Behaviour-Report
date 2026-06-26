# Behavioural Research in Climate Policy - Seminar Report

This repository contains the LaTeX source code and resources for my seminar report on the paper *"Misperceived Social Norms and Willingness to Act Against Climate Change"* (Andre et al., 2024). 

The report is written as part of the seminar **Climate and Human Behavior** (Spring 2026) at the University of Cologne.

## Project Details
- **Author:** Theo Osterhaus
- **Institution:** Faculty of Management, Economics and Social Sciences, University of Cologne
- **Instructor:** Rastislav Rehák
- **Semester:** Spring 2026

## Repository Structure
- `main.tex`: The main LaTeX document containing the text and structure of the report.
- `references.bib`: The BibLaTeX file containing all cited literature.
- `Figures/` / `plots/`: Directories for storing images, graphs, and tables used in the report.

## How to Compile
The document is set up to be compiled with `pdflatex` (or `lualatex`/`xelatex`) and uses `biber` for the bibliography. If you are compiling locally, run the following sequence:

1. `pdflatex main.tex`
2. `biber main`
3. `pdflatex main.tex`
4. `pdflatex main.tex`

Alternatively, the project is fully compatible with **Overleaf** and can be synced directly via the Overleaf-GitHub integration.

## License & Academic Integrity
This repository is created for academic purposes. Please note the university's guidelines on plagiarism and academic integrity if you intend to reference or fork this work.

Created by Gemini 3.1 Pro
