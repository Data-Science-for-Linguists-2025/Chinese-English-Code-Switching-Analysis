# Chinese-English Code-Switching Analysis of Stack Exchange Posts

**Author:** Qidu Fu  
**Email:** [email](qiduf@andrew.cmu.edu)  
**Date:** April 20, 2025

## Summary

This project analyzes Chinese-English code-switching in posts from a Chinese-language Stack Exchange site. The aim is to detect instances of code-switching, measure its frequency, and explore how different domains influence the occurrence of code-switching in this bilingual online community. The findings provide insights into multilingual communication patterns, particularly among bilingual users in online communities.

**Keywords:** Chinese-English bilinguals, code-switching, Stack Exchange, bilingual communication, online communities

## Data

The data for this project is collected using the **Stack Exchange API**, specifically querying posts from a Chinese-language focused Stack Exchange site. This dataset includes question posts from users who engage in bilingual Chinese-English discourse, providing a real-world view of code-switching in online forums. 1,000 randomly selected records of the data sourced from the API were provided in this [stack_exchange_cleaned_sample.csv](data/stack_exchange_cleaned_sample.csv) in the [data](#data) directory. 

- **Link:** [Stack Exchange API](https://api.stackexchange.com/)
- **Attribution:** Stack Exchange

## Directory

- **[final_report.md](#final_report.md)**: the comprehensive report of the project 
- [notebooks](notebooks/): The process and outcome of the project
    - [github](notebooks/0_collect_data.ipynb0_data_collection.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/0_collect_data.ipynb): experiment for scraping data from a website (This is not used in the project.)
    - [github](notebooks/1.1_collect_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/1.1_collect_data.ipynb): data collection from using the API
    - [github](notebooks/1.2_process_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/1.2_process_data.ipynb): data cleaning
    - [github](notebooks/2.1_analyze_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/2.1_analyze_data.ipynb): modeling - code-switching detection and topic modeling
    - [github](notebooks/2.2_analyze_data.ipynb) | [nbviewer](https://nbviewer.org/github/Data-Science-for-Linguists-2025/Chinese-English-Code-Switching-Analysis/blob/main/notebooks/2.2_analyze_data.ipynb): linguistic analysis - tokenization and tests
- [images](#images/): directory for images generated in this project
- [Chinese_English_CS_presentation.pptx](#Chinese_English_CS_presentation.pptx): the slide presentation of the project
- [progress_report.md](#progress_Report.md): the detailed progress made through the project
- [project_plan.md](#project_plan): the original plan developed at the beginning of the project

## References
- Bassiouney, R. (2020). Arabic sociolinguistics: Topics in diglossia, gender, identity, and politics. Georgetown University Press.
- Montanari S, Ochoa W, & Subrahmanyam K. (2019). A longitudinal investigation of language mixing in Spanish–English dual language learners: The role of language proficiency, variability, and sociolinguistic factors. Journal of Child Language, 1, 1–25. 10.1017/S0305000919000278
- Quick, A. E., Lieven, E., Carpenter, M., & Tomasello, M. (2018). Identifying partially schematic units in the code-mixing of an English and German speaking child. Linguistic Approaches to Bilingualism, 8(4), 477–501. https://doi.org/10.1075/lab.15049.qui
- Tulloch, M. K., & Hoff, E. (2023). Filling lexical gaps and more: Code-switching for the power of expression by young bilinguals. Journal of Child Language, 50(4), 981–1004. https://doi.org/10.1017/S0305000922000307
