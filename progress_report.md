# Chinese-English Code-Switching Analysis

**Qidu Fu**

## Contents
1. [1st Progress Report](#1st-progress-report)
    - [Summary of Accomplishments 1](#summary-of-accomplishments-1)
    - [Sharing Plan](#sharing-plan)
2. [2nd Proress Report](#2nd-progress-report)
    - [Summary of Accomplishments 2](#summary-of-accomplishments-2)
    - [Data Sharing](#data-sharing-partial-dataset-sharing)
3. [3rd Proress Report](#3rd-progress-report)
    - [Summary of Accomplishments 3](#summary-of-accomplishments-3)
    - [Data](#data)

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
    - **Work2.1:** [2.1_analyze_data.ipynb](2.1_analyze_data.ipynb)
- Used topics modeling methods (`KMeans`, `LDA`) to identify/cluster the topics. 
Specific code is in the Jupyter Notebook below. 
    - **Work2.2:** [2.1_analyze_data.ipynb](2.1_analyze_data.ipynb)
- Updated licensing file. Specific is in the file below. 
    - **Work2.3:** [LICENSE.md](LICENSE.md)
- Revised the `1.2_process_data.ipynb`, `project_plan.md` and `README.md` files 
to accordingly to make sure the project is doable. This began with objectives, 
timeline, and others. 
    - **Work2.4:** [1.2_process_data.ipynb](1.2_process_data.ipynb)
    - **Work2.5:** [README.md](README.md)
    - **Work2.6:** [project_plan.md](project_plan.md)
    - **Work2.7:** [progress_report.md](progress_report.md)

### Data Sharing: Partial Dataset Sharing
- **Description**: Share a subset of the dataset 1,000 records. These records 
were randomly selected (e.g., random sampling). For specific code, 
see [1.2_process_data.ipynb](1.2_process_data.ipynb). 
As noted earlier, all data were gathered using Stack Exchange API. 
- **Justification**: Balances data sharing with privacy concerns while still 
supporting open science and collaborative research. In other words, this data 
sharing plan ensures privacy and data sensitivity while still aligning with 
the principles of open science.
    - **Work2.8:** [Data Samples](data/stack_exchange_cleaned_sample.csv)


## 3rd Progress Report

### Summary of Accomplishments 3
In this second progress report, I have accomplished the following:
- Used `stanza` leveraging both its Chinese and English language models to tokenize the text data to have information on word count, 
sentence word, mean word count per sentence. 
    - **Work3.1:** [2.2_analyze_data.ipynb](2.2_analyze_data.ipynb)
    - 12,041 records/rows withou null values
    - A total word tokens of 152573
    - A total sentence counts of 13664
    - A mean word count of 10.54 per sentence
- Get the frequency counts across all domains:
    - **Work3.2:** [2.2_analyze_data.ipynb](2.2_analyze_data.ipynb)
        - Topic VS cs frequency count
        - 1) characters, synonyms, topolects            2437
        - 2) word choice, phrase, sentence structure    2033
        - 3) idioms                                     1012
        - 4) Mandarin, character                         840
        - 5) grammar, meaning                            652
        - 6) difference: writing, speech                 483
- Conduct statistical test on the frequencies across six domains 
    - **Work3.3:** [2.2_analyze_data.ipynb](2.2_analyze_data.ipynb)
    - stats, p_value: 5.0, 0.415
    - The groups are not statistically different
- Conduct POS shift analysis
    - **Work3.4:** [2.2_analyze_data.ipynb](2.2_analyze_data.ipynb)
    - no_shift    139302
    - shift        13271

### Data 
- The data file is in the final shape. No changes are made in the shared data.
- Additional data files were created for linguistic analysis and saved to avoid 
    repetive processing:
    - stack_exchange pos data
    - stack_exchange tokenized data
