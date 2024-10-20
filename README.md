# Scientific Article Repository

**Title:** Impact of ECB and FED Public Statements on Bitcoin Volatility through GenAI-powered Sentiment Analysis
**Authors:** Mgr. Vilém Krejcar, PhDr. Ladislav Krištoufek, Ph.D.  
**University:** Charles University, Faculty of Social Sciences, Institute of Economic Studies  
**Year of Submission:** 2024

## Introduction
This repository contains the article submitted to Finance Research Letters conducted at the Institute of Economic Studies (IES), which explores the impact of central banks' statements on Bitcoin through GenAI-powered sentiment analysis.

## Repository Structure
The repository is organized into the following sections:

1. **Article**
   - PDF version of the submitted article.

2. **Code**
   - Contains Jupyter notebooks for independent code execution.

3. **Data**
   - Organized into two primary folders:
     - **BaseLayer**: Early-stage datasets from raw sources, divided into Sentiment-based and Cryptocurrency-based datasets.
     - **ModellingLayer**: Processed datasets, including:
       - `finaldataset.csv`: Standardized dataset used in the modelling.
       - `finaldataset_preproc.csv`: Result of initial data processing.
       - `finaldataset_nonstand.csv`: Dataset with differenced and stationary variables.
       - `AllSpeachesSent.csv`: Dataset with final sentiment data

4. **Supporting Material**
   - Includes figures and supplementary material used in the thesis.

## Navigation
Follow these steps to replicate the analysis:

1. `01_HighFrequencyExtract.ipynb`: Extract Realized Variance and Volatility Measures.
- Please note that the core file, `Train.csv` is over 2GB, and thus is not imported into the repository
2. `02_CryptoVars.ipynb`: Collect fundamental and speculative data on Bitcoin.
3. `03_CentralBankSpeechDatasets.ipynb`: Scrape public speeches from the ECB and FED.
4. `04_SentimentAnalysis.ipynb`: Compute sentiment scores.
5. `05_DataConcatenation.ipynb`: Merge all datasets into a comprehensive final dataset.
6. `06_Modelling.ipynb`: Conduct the modelling exercise.

## Inquiries
For questions, concerns, or suggestions about the repository, please contact me at:

- **Email:** [vilem.krejcar@fsv.cuni.cz](mailto: vilem.krejcar@fsv.cuni.cz)
