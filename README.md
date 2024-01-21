# ML2024 Case Description

## Overview

The focus of this case study is on analyzing textual data from scientific papers. The primary aim is to develop an analysis pipeline that reads, pre-processes, and analyzes textual data.

## Tasks

### Data sourcing

The first stage involves sourcing and reading the textual content of scientific papers. You find a few example pdf files in ``data/``. Please download additional paper of your choice. Make sure you analyze a total of at least 6 papers.

Use an appropriate PDF reading library or tool to programmatically extract the text. You can find an example in ``solution.ipynb``, however, you are free to use any Python library you like.

### Pre-processing

Pre-processing is a critical step aimed at cleaning and preparing the text data for analysis. This stage involves:

* Removing punctuation, numbers and special characters using regular expressions.
* Converting all the text to a uniform case (usually lower case) to ensure that the analysis is not case-sensitive.
* Stop word removal, i.e. eliminating commonly used words (e.g., 'and', 'the', 'is') that do not contribute significantly to the overall meaning and can skew the analysis.
* Other potential pre-processing steps might include stemming and lemmatization, depending on the specific requirements and goals of the analysis. (optional)

### Analysis

The final stage is the analysis of the pre-processed text to extract meaningful context. This may involve:

* Frequency Analysis: Determining the most commonly occurring words or phrases, which can provide initial insights into the primary focus areas of the papers. Consider, e.g. a word cloud as a visualization.
* Contextual Analysis: Using more advanced NLP techniques such as Word Embedding or Topic Modeling to understand the context of the papers.
* Summarization: Employing algorithms to generate concise summaries of the papers, capturing the key points and findings.

Pick any method that you like (you are allowed to use ChatGPT's API as well).

## Submission

Please note that the focus of this case is on the execution of the task and NOT the results. The methods chosen are therefore of secondary importance and up to you, however, the results must be reproducible with the submitted code. You should focus on clean coding, commenting and the appropriate use of Git/GitHub. Follow the guidelines laid out in [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/).

Your solutions should be contained in one jupyter notebook ``solution.ipynb``.

Make sure to read the "Grading" section at: (https://github.com/iwh-halle/ML2024?tab=readme-ov-file#grading)