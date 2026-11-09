## Hematological Cancer Classification Using Gene Expression Data

**Project Overview**

This project investigates the classification of hematological malignancies using high-dimensional gene-expression data and machine learning techniques.

A central challenge in microarray-based classification is the high-dimensional, small-sample-size (p ≫ n) problem, where thousands of gene-expression features are available for relatively few patient samples.

The study aims to investigate how feature selection and dimensionality reduction can reduce the number of features while maintaining reliable classification performance across different hematological cancer datasets.

The project is being developed as part of a graduate-level Machine Learning course.

Project Status: In progress — data preparation and exploratory data analysis.

**Research Questions**


**RQ1:** How do different gene selection methods and hybrid approaches affect the performance of hematological cancer classification based on gene expression data?

**RQ2:** How many genes are required to achieve satisfactory classification performance for ALL/AML and DLBCL/FL, and how does this number differ between the datasets?


**Datasets**

The datasets are retrieved programmatically within the notebooks. An internet connection is required, but no API credentials or manual downloads are necessary.

**Reproducibility**

This project uses Python and a fixed random seed (42) for reproducibility.

Environment setup

Clone the repository.

Create and activate a Python virtual environment.

Install the required dependencies:


```bash
python -m pip install -r requirements.txt
```


Download the datasets following the instructions in the README.

Run the notebooks in order.

The raw datasets are not committed to the repository.