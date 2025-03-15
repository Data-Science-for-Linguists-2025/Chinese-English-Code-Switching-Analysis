# Chinese-English Code-Switching Analysis

**Qidu Fu**

## Contents
1. [1st Progress Report](#1st-progress-report)
    - [Summary of Accomplishments 1](#summary-of-accomplishments-1)
    - [Sharing Plan](#sharing-plan)
2. [2nd Proress Report](#2nd-progress-report)
    - [Summary of Accomplishments 2](#summary-of-accomplishments-2)
    - [Data Sharing](#data-sharing-partial-dataset-sharing)

## 1st Progress Report

### Summary of Accomplishments 1
In this first progress report, I have accomplished the following:
- Experimented with web scraping using `BeautifulSoup` on a forum of posts 
    and comments by Chinese students (or soon-to-be students) studying abroad. 
    This data is not used in the project. 
    - **Work0:** [0_collect_data.ipynb](0_collect_data.ipynb)
- Collected the first dataset from Stack Exchange via its API, obtaining about 
    12,400 records of Chinese-English code-switching posts. 
    - **Work1.1:** [1.1_collect_data.ipynb](1.1_collect_data.ipynb)
- Integrated two additional datasets from previous Chinese-English 
    code-switching studies (GitHub and HuggingFace). 
    These two datasets may be used to complement for the stack 
    exchange dataset. 
    - **Work1.2:** [1.2_process_data.ipynb](1.2_process_data.ipynb)
- Processed the stack exchange dataset to clean it saved the first 100 
    rows data as samples. For specific steps and code, see the Jupyter Notebook.   
    - **Work1.2:** [1.2_process_data.ipynb](1.2_process_data.ipynb)
    - **Work1.2:** [Data Samples](data_samples/stack_exchange_cleaned_sample.csv)
- Revised the `project_plan.md` and `README.md` files to according to the new
    dataset. This began with new research questions, objectives, timeline, and
    others. 
    - **Work1.3:** [README.md](README.md)
    - **Work1.3:** [project_plan.md](project_plan.md)
    - **Work1.3:** [progress_report.md](progress_report.md)

### Sharing Plan: Partial Dataset Sharing

- **Description**: Share a subset of the dataset, focusing on the first 
1,000 records.
- **Justification**: Balances data sharing with privacy concerns while still 
supporting open science and collaborative research. In other words, this data 
sharing plan ensures privacy and data sensitivity while still aligning with 
the principles of open science.


## 2nd Progress Report

### Summary of Accomplishments 2
In this second progress report, I have accomplished the following:
- Used **regex** and **language detection libraries** (`langdetect`, `langid`) 
to identify/detect if sentences are CS or not. Specific code is in the Jupyter 
Notebook below. 
    - **Work1:** [2.1_analyze_data.ipynb](2.1_analyze_data.ipynb)
- Used topics modeling methods (`KMeans`, `LDA`) to identify/cluster the topics. 
Specific code is in the Jupyter Notebook below. 
    - **Work2:** [2.1_analyze_data.ipynb](2.1_analyze_data.ipynb)
- Updated licensing file. Specific is in the file below. 
    - **Work3:** [LICENSE.md](LICENSE.md)
- Revised the `1.2_process_data.ipynb`, `project_plan.md` and `README.md` files 
to accordingly to make sure the project is doable. This began with objectives, 
timeline, and others. 
    - **Work4.3:** [1.2_process_data.ipynb](1.2_process_data.ipynb)
    - **Work4.3:** [README.md](README.md)
    - **Work4.3:** [project_plan.md](project_plan.md)
    - **Work4.3:** [progress_report.md](progress_report.md)

### Data Sharing: Partial Dataset Sharing
- **Description**: Share a subset of the dataset, focusing on the first 1,000 
records. As noted earlier, all data were gathered using Stack Exchange API. 
- **Justification**: Balances data sharing with privacy concerns while still 
supporting open science and collaborative research. In other words, this data 
sharing plan ensures privacy and data sensitivity while still aligning with 
the principles of open science.
    - **Work:** [Data Samples](data_samples/stack_exchange_cleaned_sample.csv)
