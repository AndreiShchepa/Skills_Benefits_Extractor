# Extraction of Skills and Benefits from Job Postings Descriptions

## Overview
This project analyzes job descriptions to efficiently extract relevant skills and benefits using NLP techniques. The solution is optimized for performance to enable rapid job matching and processing.

## Data Source
The project uses the Indeed Job Posting Dataset available on Kaggle:
[Indeed Job Posting Dataset](https://www.kaggle.com/datasets/promptcloud/indeed-job-posting-dataset)

## Key Features

### Skills and Benefits Extraction
- Implements advanced NLP techniques (including BERT embeddings) for accurate extraction
- Ensures non-overlapping identification of skills and benefits
- Provides clear separation between different types of job attributes

### Performance Optimization
- Batch Processing
- Adding LRU cache and pre-computed reference embeddings
- Parallel Processing
- Vectorized Similarity Computation

### Validation System
Quality assurance is maintained through:
- Random sampling of job postings for validation
- Manual annotation process
- Performance metrics calculation:
  - Precision
  - Recall
  - F1-score

## Getting Started
- Python 3.8+
- Access to Kaggle or Google Colab
- Set correct paths to **benefits.txt** and **job_labels.json** files

`mvi-sp/`\
├── `main.ipynb` -> Python notebook with code\
├── `job_labels.json` -> Manual annotations for validation\
├── `benefits.txt` -> List of predefined benefits\
├── `report.pdf` -> Report
