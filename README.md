# Implementierung eines Dashboards für Pentesting in einer Digital Forensik und Incident Response (DFIR) Umgebung für Open RAN

Bachelor Thesis, Bachelor Technische Informatik, Computer Networks Research Group, Forschungsprojekt 5G-FORAN, TH Köln, WS2024/25

This repository contains all LaTeX files and resources for my Bachelor’s thesis on implementing a dashboard for pentesting within a Digital Forensic and Incident Response (DFIR) environment, focusing on Open RAN (Radio Access Networks). The project is part of the 5G-FORAN research initiative, conducted within the Computer Networks Research Group at the TH Köln during the Winter Semester 2024/25.

## Repository Structure

- **content/**: Contains individual chapter files in `.tex` format. Each file represents a different section or chapter of the thesis for modular editing and compilation.
- **images/**: Folder for images, and other visual assets referenced in the thesis.
- **data/**: Folder for not image format assets, mainly ACEMA-generated diagrams and raw data used in the thesis.
- **Abschlussarbeit.tex**: Main LaTeX file that compiles the entire thesis document by including files from the `content` folder and applying configurations from other `.tex` files.
- **definitions.tex**: Contains custom definitions, macros, and LaTeX commands specific to the thesis.
- **glsdefs.tex**: File for glossary and acronyms definitions.
- **packages.tex**: Specifies all LaTeX packages required for the thesis document.
- **references.bib**: Bibliography file with references in BibTeX format, used for citation within the thesis.

## Usage

1. **Compile the thesis**:
   Ensure you have a LaTeX editor or compiler installed (e.g., TeXShop, Overleaf, or command-line tools like `pdflatex` or `latexmk`). Run the following command to compile the main document:
   
   ```bash
   pdflatex Abschlussarbeit.tex
   bibtex Abschlussarbeit
   pdflatex Abschlussarbeit.tex
   pdflatex Abschlussarbeit.tex
