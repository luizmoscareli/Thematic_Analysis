# Qualitative Thematic Analysis – MSc Thesis

This repository contains the Python scripts used for the **qualitative thematic analysis** in my MSc thesis:  
*Beyond Adoption – How Audit AI Tools are Implemented and Used in Practice.*

The analysis is based on interview transcripts exported from NVivo and follows **Braun & Clarke’s (2006)** six-phase thematic analysis framework. The code automates descriptive, comparative, and co-occurrence analyses of coded qualitative data.

## Contents
- `Python - Qualitative Analysis.docx` – Annotated Python code for all thematic analysis steps.
- **Note:** The original interview transcripts are confidential and are not included in this repository. A placeholder dataset with the same structure can be provided upon request for demonstration purposes.

## Main Features

### 1. Frequency Descriptives
- Theme frequency counts and visualizations.
- Top 15 most frequent codes.
- Theme frequency split by interviewee group (*Auditors* vs. *Innovation Team*).
- Quote density per interviewee.

### 2. Grouped Comparisons
- Theme frequency by interviewee group × seniority level.
- Frequency and percentage tables for each theme.
- Code frequency heatmaps (raw and normalized) for top 15 codes.

### 3. Seniority-Based Analysis (Auditors Only)
- Code frequency by auditor seniority (raw counts and normalized frequencies).
- Heatmaps for top 15 codes in each comparison.

### 4. Co-Occurrence Analyses
- Theme co-occurrence matrix by quote.
- Code co-occurrence matrix for the top 15 codes.
- Theme frequency by interviewee matrix.

### 5. Visual Outputs
- All analyses produce publication-ready visualizations using Matplotlib and Seaborn with a consistent blue color palette.

## Requirements
- Python 3.10+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
