# Project Plan: Code-Switching Analysis 

## Project Overview

The goal of this project is to analyze code-switching between Chinese and 
English in social media posts made by Chinese students. The analysis will 
focus on detecting code-switching, measuring its frequency, 
and understanding how contexts/topics
influences the use of code-switching.

Keywords: **bilingual students**, **code-switching**, 
**Chinese-English**, **multilingual communication**

## Research Questions

1. **How frequently does code-switching occur in social media posts by Chinese students?**
2. **Is there a significant difference in code-switching frequency in posts across different domains?**

## Why is this Important?

### 1. **Cultural Identity & Social Dynamics**
   This project sheds light on how students express 
   their **multilingual identity** and navigate their cultural 
   spaces by switching languages. Understanding these patterns can help 
   us see how students use code-switching for **peer bonding**, 
   **cultural adaptation**, and **identity expression**, particularly in a 
   foreign context like the **U.S.** or **Canada**.

### 2. **Educational Insights**
   Understanding how students switch languages in different contexts 
   can guide universities in providing **effective bilingual support** 
   and creating more **inclusive academic environments** for multilingual 
   students, especially in **foreign countries**. 
   This includes supporting **international students** from 
   countries like **China** studying abroad in the **U.S.** or **Canada**.

## Steps and Timeline

### **Step 1: Data Collection & Preprocessing (3 weeks)**

- **Task**: Gather social media posts made by Chinese students 
and preprocess the data.
- **Details**:
  - Collect posts from online forums. 
    - 1. [1point3acres Forum - Forum 27](https://www.1point3acres.com/bbs/forum-27-1.html)
    - 2. [1point3acres Forum - Forum 29](https://www.1point3acres.com/bbs/forum-29-1.html)
  - Clean the data (remove irrelevant characters, emojis, URLs).
  - Apply **language detection** to identify the Chinese and English parts of the text.

### **Step 2: Code-Switching Detection & Frequency Analysis (3 weeks)**

- **Task**: Detect code-switching instances and analyze the frequency.
- **Details**:
  - Implement a **rule-based detection system** to flag code-switching 
  by detecting language shifts between Chinese and English within each post.
  - Use **language detection tools** (e.g., `langdetect`, `langid`) 
  on a sentence level or sliding window approach to identify code-switching.
  - Calculate the **frequency** of code-switching in the dataset 
  and identify patterns in the data.

### **Step 3: Domain Classification & Reporting (4 weeks)**

- **Task**: Classify posts into categories based on their topics and prepare a final report.
- **Details**:
  - Classify posts into different discourse domains through topic modeling.
  - **Analyze** the frequency of code-switching across different domains.
  - **Prepare a final report** summarizing the findings, methodology, and insights.

## Deliverables

1. **Code-Switching Detection Model**: A simple model to detect code-switching 
between Chinese and English in social media posts.
2. **Frequency Analysis Report**: A report showing how often code-switching 
occurs and its relationship with different discourse domains (personal vs. academic).
3. **Final Report**: A detailed summary of the project, including insights 
into code-switching frequency, context analysis, 
and implications for multilingual communication.

## Timeline

| **Phase**                     | **Task**                                                      | **Duration**       |
|-------------------------------|---------------------------------------------------------------|--------------------|
| **Step 1**: Data Collection    | Collect and preprocess the data                                | 3 weeks            |
| **Step 2**: Code-Switching Detection | Detect code-switching and perform frequency analysis        | 3 weeks            |
| **Step 3**: Domain Classification & Reporting | Classify posts, analyze frequency, and prepare the final report | 4 weeks            |
| **Total Duration**             |                                                               | **10 weeks**        |

