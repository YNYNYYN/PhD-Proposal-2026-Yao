# PhD Research Proposal

**Title:** Digital Twins for Historic Buildings: A Comprehensive Framework Integrating Structural Health, Microclimate, and Energy Performance

**Author:** Yao Nie

**Target Year:** 2026

**Intended Supervisor:** Dr Federico Tartarini

## 📖 Overview
This repository contains the LaTeX source code, figures, and bibliographic data for my PhD research proposal. The document outlines the background, objectives, methodology, and expected contributions of the proposed study.

## 📂 Project Structure
The project is organised modularly to ensure clarity and maintainability:

* **`main.tex`**: The root file that compiles the entire document.
* **`section*.tex`**: Individual chapters (Introduction, Methodology, Work Plan, etc.).
* **`figures/`**: Contains all high-resolution diagrams and plots used in the proposal.
* **`references.bib`**: The BibTeX file containing all academic references.

## 🚀 How to Compile

### Option 1: Overleaf (Recommended)
You can upload this entire repository (as a `.zip` file) directly to Overleaf. The project is configured to compile with `pdfLaTeX`.

### Option 2: Local Compilation
If you prefer to compile locally, please ensure you have a standard LaTeX distribution (like TeX Live or MiKTeX) installed.

Run the following commands in your terminal:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
