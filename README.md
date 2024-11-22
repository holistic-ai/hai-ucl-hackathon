<h1 align="center">
<img src="logo.png" width="300">
<br>
Holistic AI x UCL AI Society Hackathon 2024
</h1>

Website: [Holistic AI UCL Hackathon](https://hackathon.holisticai.com/)

This repository contains the code and resources for the **UCL AI Society and Holistic AI Hackathon 2024**. Below are the details of each track, datasets, and linked Jupyter notebooks.

---

## Track 1: Multi-Objective Optimization for AI Trustworthiness in Tabular Data Classification

The goal of this track is to develop a multi-objective optimization algorithm to improve the **trustworthiness** of AI models in tabular data classification tasks. The algorithm will optimize the model's **performance**, **fairness**, **robustness**, **privacy**, **security**, and **explainability** simultaneously.

### Datasets and Tasks

- [**Bank Marketing Dataset**](track1_multi_objective_optimization/Bank_Dataset.ipynb):  
  The primary goal when working with the Bank Marketing dataset is to predict whether a client will subscribe to a term deposit based on the input features from the dataset.

- [**Minimum Wage Dataset**](track1_multi_objective_optimization/Minimum_Wage_Dataset.ipynb):  
  The primary goal of analyzing the Minimum Wage dataset is to predict whether a worker’s average income falls above or below five times the minimum wage threshold.

- [**Compas Dataset**](track1_multi_objective_optimization/Compas_Dataset.ipynb):  
  The primary goal of analyzing the Compas dataset is to predict whether a defendant will re-offend within two years, based on the input features from the dataset.

---

## Track 2: Building Trustworthy Models for Stereotype Classification in Text Data

This track focuses on creating ethical and trustworthy AI systems for detecting stereotypes in text data. Participants will work with the **Expanded Multi-Grain Stereotype Dataset (EMGSD)** to classify text as containing stereotypes, being neutral, or unrelated, while addressing key ethical considerations.

### Datasets and Tasks

- [**Main Text Stereotype Detection**](track2_text_stereotype_classification/Main_Text_Stereotype_Detection.ipynb):  
  Classify text in the EMGSD dataset as containing stereotypes, neutral, or unrelated. Focus on building a robust and ethical classifier.

- [**Scraping Biased Data**](track2_text_stereotype_classification/Extra_Scraping_Biased_Data.ipynb):  
  Implement scraping methods to collect and preprocess biased text data from online sources for potential inclusion in the MGSD dataset.

- [**Generate Biased Data**](track2_text_stereotype_classification/Extra_Generate_Biased_Data.ipynb):  
  Fine-tune a biased GPT-2 model on stereotype-labeled data to generate additional biased text. This generated data can be used to enhance the MGSD dataset.


---

### Instructions

1. Clone the repository:
```bash
git clone https://github.com/holistic-ai/hai-ucl-hackathon.git
```

2. cd into the repository:
```bash
cd hai-ucl-hackathon
```

3. Install required dependencies (ensure Python 3.10+ is installed):

```bash
pip install -r requirements.txt
```

4. Navigate to the relevant notebook and open it using Jupyter Notebook or JupyterLab:

```bash
jupyter notebook track1_multi_objective_optimization/Bank_Dataset.ipynb
```

For more details, visit the official website: Holistic AI UCL Hackathon

This version includes direct links to each file in the repository for easy navigation and clear task descriptions. Let me know if you’d like any further edits!