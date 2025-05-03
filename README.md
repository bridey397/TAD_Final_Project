# Text as Data Final Project: Diversity, Equity, and Inclusion Meanings in Political Texts
Final Project Repo for Text as Data Class

## Description

This repository includes materials to analyze the meanings of the words "diversity", "equity", and "inclusion" across documents pulled from the Federal Register API to determine if the meaning of the words is consistent across groups and over time. It includes raw data, code files, clean data, figures, presentation, and report.

## Research Questions

1. What is the meaning of the words diversity, equity, and inclusion across political texts?
2. Does this meaning vary with the President in power? In this case, Trump (first term) versus Biden?
3. What are the topics of political documents that use these words?

## Repository Structure & File Contents

### Project Folder Structure

#### `Code`
Includes all code files used to pull data from the Federal Register API and create visualizations.

- `01_API.ipynb`: Python file used to pull data from Federal Register.  
- `02_Data_Cleaning.rmd`: RMD file used to clean data and create visualizations from KWIC, word embeddings, and LDA.

---

#### `Final_Paper`
Includes final paper RMD file. PDF to be sent via email.

- `Final_Paper.Rmd`: RMD file containing final paper with findings, results, and discussion.

---

#### `Outputs`
Includes visualizations for all code as JPG files.

**Keyword-in-Context (KWIC) Bar Plots:**
- `fg01-diversity-kwic.jpg`
- `fg02-equity-kwic.jpg`
- `fg03-inclusion-kwic.jpg`

**LDA Topic Modeling (Abstracts):**
- `fg04-inclusion-abstract-LDA.jpg`
- `fg05-equity-abstract-LDA.jpg`
- `fg06-diversity-abstract-LDA.jpg`

**Causal Word Embeddings (President as Binary Variable):**
- `fg07-inclusion-causal-embeddings.jpg`
- `fg08-equity-causal-embeddings.jpg`
- `fg09-diversity-causal-embeddings.jpg`

**LDA Topic Modeling (Keyword-Focused on Excerpts):**
- `fg10-inclusion-excerpts-LDA-keyword.jpg`
- `fg11-equity-excerpts-LDA-keyword.jpg`
- `fg12-diversity-excerpts-LDA-keyword.jpg`

---

#### `Presentation`
Includes presentation slides for in-class presentation. (Note: HTML file too large to include.)

- `Presentation.qmd`: QMD file with presentation slides.

---

#### `Project_Proposal`
Includes original project proposal.

- `TAD_Final_Project_Proposal.pdf`: PDF file with original project proposal.

---

#### `Raw_Data`
Includes raw data from API pull for each focal word.

- `diversity_data.json`: JSON file with diversity corpus.  
- `equity_data.json`: JSON file with equity corpus.  
- `inclusion_data.json`: JSON file with inclusion corpus.

## Author

Bridgette Sullivan

## Course & Institutional Information

This project was produced as part of the spring 2025 **PPOL 6801: Text as Data: Computational Linguistics** course at **McCourt School of Public Policy** at **Georgetown University**.

## References

