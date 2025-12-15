# LLMs Are Not Weird Workbook
This repository contains 3 files for the paper "LLMs Are Not Weird." These are as follows:

1. Submission_3_Main_v0.xlsx (Excel file): This is the main Excel file, that is used by the Python code (Submission_3 Analysis) below.
2. Submission_3 Analyis_v0.ipynb (Python file): This file is the main code file, which works using the data from Submission_3_Main_v0.xlsx.
3. raw_data_combined.xlxs. This Excel file is not for any calculation. It is just the raw data, in case you are interested to see the individual responses of the LLMs.
## 1. Submission_3_Main_v0.xlsx
This Excel sheet contains 5 sheets: 
### 1.A. File Description
This Excel workbook contains the main processed and organized data that is used by the code. 
### 1.B. Worksheets Included
The workbook contains the following sheets:
- Trimmed Mean: This is the main sheet that is used by the code. It contains the trimmed responses of 
   a. LLMs, which are derived from 3. raw_data_combined.xlsx below. 
   b. and humans, which are retrieved from https://www.uni-trier.de/universitaet/fachbereiche-faecher/fachbereich-iv/faecher/betriebswirtschaftslehre/team/fin/forschung/research-data. 
- Hyperbolic: This sheet contains the delta and beta results, which are obtained from the raw data ( raw_data_combined.xlsx)
- Expected Values: These are the responses of the LLMs and humans compared with the expected values of the questions 5-12. 
## 2. Submission_3 Analyis_v0.ipynb (Python file)
Main Code file
## 3. raw_data_combined.xlsx
### 3.A. File Description
This Excel workbook contains numeric responses from multiple Large Language Models (LLMs) answering a 14-question behavioral economics questionnaire.
Each worksheet corresponds to a specific model and temperature condition.
Each row represents one trial, and each column (Q1–Q14) represents one numeric answer produced by the model.
### 3.B. Worksheets Included
The workbook contains the following sheets:
DeepSeek Reasoner (Temperatures 0 to 2)
deepseek_0_temp
deepseek_0_5_temp
deepseek_1_temp
deepseek_1_5_temp
deepseek_2_temp
Gemini (Temperatures 0 to 2)
gemini_0_temp
gemini_0_5_temp
gemini_1_temp
gemini_1_5_temp
gemini_2_temp
GPT-4.0 (Temperatures 0 to 2)
gpt4_0_temp
gpt4_0_5_temp
gpt4_1_temp
gpt4_1_5_temp
gpt4_2_temp
GPT-4o (Temperatures 0 to 2)
gpt4o_0_temp
gpt4o_0_5_temp
gpt4o_1_temp
gpt4o_1_5_temp
gpt4o_2_temp
Names may vary slightly depending on your export, but each follows the same pattern.
3. Sheet Structure
Every worksheet uses the same format:
Column A: Trial (trial number)
Columns B–O: Q1–Q14, the numeric answers provided by the LLM for each question
All values in Q1–Q14 are numeric and have been extracted from the original text outputs.
4. Notes
Each model–temperature combination has its own sheet.
Trials within each sheet are independent runs of the same questionnaire.



All model outputs were generated between October 5 and October 9, 2025. Dates are reported in ISO 8601 format (YYYY-MM-DD).
•	GPT-5: 2025-10-05
•	Gemini (all temperatures): 2025-10-05
•	DeepSeek Reasoner (all temperatures): 2025-10-08
•	GPT-4.0 (all temperatures): 2025-10-09
•	GPT-4o (all temperatures): 2025-10-09"

## Citation
If you use this dataset, please cite:

Erdem et al. (2025). “LLMs Are Not Weird: Comparing AI and Human Financial Decision-Making.”
