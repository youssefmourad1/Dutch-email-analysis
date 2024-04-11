# Dutch-email-analysis

Here's a README.md that you can use for your repository, along with a simple `requirements.txt`:

### README.md

# Dutch Email Question Analysis

This repository contains code for analyzing Dutch email data, specifically focusing on extracting questions from emails, determining similarity among them, and identifying the most frequently occurring questions.

## Overview

The analysis involves several steps:
- Loading the dataset from an Excel file.
- Extracting questions from the email body.
- Preprocessing the questions for analysis.
- Vectorizing the questions using TF-IDF.
- Computing cosine similarity among the vectorized questions.
- Clustering similar questions based on a similarity threshold.
- Identifying and visualizing the most frequently occurring questions.

## Prerequisites

- Python 3
- pandas
- scikit-learn
- numpy
- matplotlib

## Installation

Clone this repository and install the required Python packages:

```
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebook `deutch_email_analysis.ipynb`:

```
jupyter notebook deutch_email_analysis.ipynb
```

or if you prefer to run it as a Python script, convert it to `.py` format and run:

```
jupyter nbconvert --to script deutch_email_analysis.ipynb
python deutch_email_analysis.py
```

## Dataset

The analysis is based on a dataset contained in 'Data sample (1).xls', which should be placed in the same directory as the script. This dataset is expected to have a column named 'MsgBodyPlainText' containing the text of emails.
