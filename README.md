# Part 2: D2C Customer Churn Intelligence - RFM Segmentation & Strategy

## Project Overview
This repository contains the transactional customer segmentation engine and targeted retention strategy phase for the D2C Personal-Care Brand Customer Churn project. The objective of this milestone is to construct behavioral customer groups via empirical RFM metric modeling and multi-channel customer service complaint cross-referencing to determine ROI-maximizing budget allocation plans.

## Project Structure
The repository contains the following core assignment deliverables:
* `rfm_segmentation.ipynb`: Jupyter notebook containing the complete data pipeline, aggregation steps, segment allocation, and 6 core cohort verification plots.
* `segments.csv`: Processed spreadsheet output compiling all unique 2,400 customer records alongside their recency, frequency, monetary, ticket counts, and mapped cohort names.
* `retention_strategy.md`: Professional business report detailing optimal budget allocations across tiers using non-arbitrary empirical logic.
* `manual_review_cases.md`: Deep-dive edge-case evaluation log detailing 10 critical operational customer profiles needing human intervention.
* `requirements.txt`: Standard list of environment package dependencies.

## Setup & Running Instructions
To execute the processing notebooks locally, use a Python 3.x environment and implement the following steps:

1. Download or clone this public repository.
2. Put your source `orders.csv` and `support_tickets.csv` files directly in the root directory.
3. Install the environment dependencies via terminal command:
   ```bash
   pip install -r requirements.txt
   4.Launch and run the analysis notebook:
   jupyter notebook rfm_segmentation.ipynb
