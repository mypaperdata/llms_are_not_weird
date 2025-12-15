# LLMs Are Not Weird – Workbook

This repository contains replication materials for the paper (for Windows only)
**“LLMs Are Not Weird: Comparing AI and Human Financial Decision-Making.”**

---

## Files

1. `Submission_3_Main_v0.xlsx`  
   Main processed dataset used by the analysis.

2. `Submission_3_Analysis_v0.ipynb`  
   Python notebook that performs the analysis using `Submission_3_Main_v0.xlsx`.

3. `environment.yml`  
   Conda environment file for reproducibility.

4. `raw_data_combined.xlsx`  
   Raw LLM responses provided for transparency only. This file is **not required** to run the analysis.

---

## How to Run (Recommended)

```bash
conda env create -f environment.yml
conda activate clustering
jupyter notebook
```

Then open Submission_3_Analysis_v0.ipynb and run all cells.

## Detailed Explanation (Optional)

### 1. Submission_3_Main_v0.xlsx
This Excel sheet contains 5 sheets: 
#### 1.A. File Description
This Excel workbook contains the main processed and organized data that is used by the code. 
#### 1.B. Worksheets Included
The workbook contains the following sheets:
- Trimmed Mean: This is the main sheet that is used by the code. It contains the trimmed responses of 
   a. LLMs, which are derived from 3. raw_data_combined.xlsx below. 
   b. and humans, which are retrieved from https://www.uni-trier.de/universitaet/fachbereiche-faecher/fachbereich-iv/faecher/betriebswirtschaftslehre/team/fin/forschung/research-data.
  These data are calculated using mean trimming of 10% (10% bottom and 10% top)
- Hyperbolic: This sheet contains the delta and beta results, which are obtained from the raw data ( raw_data_combined.xlsx)
- Expected Values: These are the responses of the LLMs and humans compared with the expected values of the questions 5-12. 
### 2. Submission_3 Analysis_v0.ipynb (Python file)
Main Code file
### 3. raw_data_combined.xlsx
#### 3.A. File Description
This Excel workbook contains numeric responses from multiple Large Language Models (LLMs) answering a 14-question behavioral economics questionnaire.
Each worksheet corresponds to a specific model and temperature condition.
Each row represents one trial, and each column (Q1–Q14) represents one numeric answer produced by the model.
#### 3.B. Worksheets Included
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
•	GPT-4o (all temperatures): 2025-10-09

## Citation
If you use this dataset, please cite:

Erdem and Ashok (2025). “LLMs Are Not Weird: Comparing AI and Human Financial Decision-Making.”
