# CRM & CM with Business Intelligence – Individual Coursework Case Study

## Market Analysis and Stock Segmentation Using RFM

This repository contains my individual coursework case study for the University of Westminster module **CRM & CM with Business Intelligence (6BUIS017W)**.

The project focuses on analysing S&P 500 stocks using Python in Google Colab, applying financial metrics, adapted Recency, Frequency and Monetary (RFM) analysis, and machine learning clustering techniques.

## Project Overview

The coursework consists of three main tasks:

**Task 1: Data Preparation and Feature Engineering**
- Acquiring and validating historical S&P 500 stock data using Yahoo Finance.
- Calculating mean weekly returns and weekly beta.
- Adapting Recency, Frequency and Monetary (RFM) metrics to measure unusual trading activity.

**Task 2: Stock Segmentation and Sensitivity Analysis**
- Preparing and standardising financial and RFM features.
- Applying Ward's Agglomerative Clustering and K-Means.
- Comparing cluster profiles and algorithm agreement.
- Conducting correlation and sensitivity analysis, including removing Monetary.

**Task 3: Business Intelligence and Critical Review**
- Proposing a data mart to support financial analysis.
- Evaluating stock segments and sector composition.
- Discussing business applications, limitations and reproducibility.

## Study Period and Observation Date

- **Study period:** 1 January 2021 – 31 December 2024.
- **RFM observation date:** 31 December 2024.
- **RFM analysis window:** Final 60 trading sessions (7 October – 31 December 2024).
- **High-volume event threshold:** Daily volume strictly exceeding twice the mean volume of the preceding 20 trading sessions, excluding the assessed day.
- **Final eligible dataset:** 494 shares.

## Repository Contents

- `CRM1_Codes.ipynb` – Google Colab notebook containing the Python implementation, calculations, clustering and visualisations.
- `data/` – Supporting datasets, feature tables, cluster assignments, validation outputs and figures.
- `requirements.txt` – Python libraries and dependencies required to run the notebook.
- `README.md` – Project documentation and instructions.

### What's Inside the `data/` Folder?

The `data/` directory contains supporting outputs from the coursework, including:

- Historical stock price data and acquisition records.
- Calculated mean weekly returns, beta and RFM features.
- Prepared feature matrices.
- Ward and K-Means cluster assignments.
- Algorithm comparison and evaluation results.
- Correlation and sensitivity analysis outputs.
- Supporting charts and visualisations.

These files provide evidence for the calculations and findings presented in the coursework report.

## How to Run the Notebook

1. Open `CRM1_Codes.ipynb` in Google Colab.
2. Ensure the Python libraries listed in `requirements.txt` are installed.
3. Upload or make the required input files available if prompted by the notebook.
4. Run the notebook cells sequentially, from top to bottom.
5. Review the generated calculations, tables, figures and clustering results.

To install the dependencies, use:

```bash
pip install -r requirements.txt
```

## Reproducibility and Limitations

The repository includes the Python implementation and supporting outputs to improve transparency and reproducibility.

Historical stock prices were obtained using Yahoo Finance, while S&P 500 constituent information was sourced from Wikipedia.

Results may differ if the analysis is rerun using updated market data or a different constituent list. The use of current index constituents to analyse historical periods also introduces potential survivorship bias.

The findings describe historical stock characteristics and trading activity. They should not be interpreted as predictions of future investment performance.

---

**University of Westminster | Academic Year 2026/27**

Thank you for viewing my coursework repository!
