# Tracking Global Priorities: Analyzing SDG Representation in UNGA Speeches Using Text Mining 🚀

### Barcelona School of Economics (Cohort 2025)
### Introduction to Text Mining and Natural Language Processing

## Project Overview
This project analyzes UNGA speeches to track the representation of key global issues over time using text mining. By constructing and refining SDG-based dictionaries with TF-IDF, we examine how topics like climate change, gender equality, health crises, and economic shifts appear in UN discourse. The study assesses whether major global events influence UN rhetoric and tests the applicability of broader topic dictionaries.

## Structure
1. **NLP_2_Dictionary.ipynb**  
   - Required file: `sdg_key.csv`  
   - Running this notebook will generate the file `sdg_dictionaries.json`.

2. **NLP_2_Analysis.ipynb** (or its updated versions)  
   - Required file: `UNGDC_1946-2023.csv`  
   - This notebook consumes `sdg_dictionaries.json` and outputs two JSON files:
     - `filtered_sdg_dictionaries.json`
     - `sdg_dict_w_json.json`

### Source for UNGDC_1946-2023.csv - https://www.kaggle.com/code/namigabbasov/topic-modeling-in-r/input

## Notes
- Ensure all required files (`sdg_key.csv` and `UNGDC_1946-2023.csv`) are placed in the same directory as the notebooks.

Happy analyzing! :)
