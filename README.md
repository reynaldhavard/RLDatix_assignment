# RLDatix assignment

## Assignment Overview:
You’ve been asked to help a clinical data team develop an AI assistant that:	
1. Predicts whether a patient will be readmitted to hospital within 30 days	
2. Extracts and categorises key information from free-text discharge notes.	
This assignment combines a binary classification problem with a lightweight NLP/LLMbased task, both based on the same dataset.	


## Repository

This repository contains:
- the dataset in `Assignment_Data.xlsx`
- information about the assignment in `Data_Science_Assignment.pdf`
- a notebook `rldatix_task.ipynb` containing the code for the assignment as well as comments
- a `requirements.txt` file indicating the necessary Python packages to run the notebook
- `Report_RLDatix_Reynald_Havard.pdf` is the report for the assignment.


### How to run the notebook

- Install the package using `pip install -r requirements.txt`
- Execute the cells in `rldatix_task.ipynb` from top to bottom
- 8 GB of VRAM are necessary to run the LLM (tested on GPU only)