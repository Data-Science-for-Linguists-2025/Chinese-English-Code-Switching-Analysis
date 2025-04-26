# Chinese-English Code-Switching Analysis: The Case of Stack Exchange Posts

**Author:** Qidu Fu  
**Email:** qiduf@andrew.cmu.edu  
**Date:** April 15, 2025

## Summary

This project analyzes Chinese-English code-switching in posts from a Chinese-language Stack Exchange site. The aim is to detect instances of code-switching, measure its frequency, and explore how different domains influence the occurrence of code-switching in this multilingual online community. The findings provide insights into multilingual communication patterns, particularly among multilingual users in online communities.

**Keywords:** Chinese-English , code-switching, Stack Exchange, multilingual communication, online communities

## Data

The data for this project is collected using the **Stack Exchange API**, specifically querying posts from a Chinese-language focused Stack Exchange site. This dataset includes question posts from users who engage in multilingual Chinese-English discourse, providing a real-world view of code-switching in online forums. The scraped data included two columns: the text posted and its assigned tags by the users, with 12,401 posts. (For more information, see the [final_report.md](final_report.md).) 1,000 randomly selected records of the data sourced from the API were provided in this [stack_exchange_cleaned_sample.csv](data/stack_exchange_cleaned_sample.csv) in the [data](data/) directory. 

- **Link:** [Stack Exchange API](https://api.stackexchange.com/)
- **Attribution:** Stack Exchange

## Directory

- **[final_report.md](#final_report.md)**: the comprehensive report of the project 
- [notebooks](notebooks/): the process and outcome of the project
    - 0_collect_data.ipynb [github](notebooks/0_collect_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/ff9caf7466e974b2a63627bd47a40c5941afd29a/notebooks/0_collect_data.ipynb): experiment for scraping data from a website (This is not used in the project.)
    - 1.1_collect_data.ipynb [github](notebooks/1.1_collect_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/ff9caf7466e974b2a63627bd47a40c5941afd29a/notebooks/1.1_collect_data.ipynb): data collection from using the API
    - 1.2_process_data.ipynb [github](notebooks/1.2_process_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/06e28eccea6bdfab3ab529cc55cb8bca543dc4f5/notebooks/1.2_process_data.ipynb#2-process-the-stack-exchange-data-the-title-column): data cleaning
    - 2.1_analyze_data.ipynb [github](notebooks/2.1_analyze_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/2.1_analyze_data.ipynb): modeling - code-switching detection and topic modeling
    - 2.2_analyze_data.ipynb [github](notebooks/2.2_analyze_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/2.2_analyze_data.ipynb): linguistic analysis - tokenization and tests
- [data](data/): directory for 1,000 records of sample data
- [images](images/): directory for images generated in this project
- [Chinese_English_CS_presentation.pdf](Chinese_English_CS_presentation.pdf): the slide presentation of the project
- [LICENSE.md](LICENSE.md): GPL-3.0 license used for this project
- [README.md](README.md): the readme file for this project
- [progress_report.md](progress_report.md): the detailed progress made through the project
- [project_plan.md](project_plan.md): the original plan developed at the beginning of the project

## Guestbook
Feel free to leave any comments, feedback, and suggestions on this [guestbook](https://github.com/Data-Science-for-Linguists-2025/Class-Lounge/blob/main/guestbooks/qidu.md).
