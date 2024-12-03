<h1 align="center">
<img src="hackathon-tutorials/logo.png" width="300">
<br>
Holistic AI x UCL AI Society Hackathon 2024
</h1>

Website: [Holistic AI UCL Hackathon](https://hackathon.holisticai.com/)

Welcome to the **Holistic AI x UCL AI Society Hackathon 2024**! This repository contains all the code, datasets, and resources needed to participate. Whether you're a seasoned data scientist or a beginner with no coding experience, we've got you covered.

- **Join the hackathon’s communication channels**:  
  For live support from mentors during the event, join our Slack community:  
  [Holistic AI Community Slack](https://join.slack.com/t/holisticaicommunity/shared_invite/zt-2jamouyrn-BrMfeoBZIHT8HbLzB3P9QQ)

  
## **Project Showcase**

This section highlights the outstanding projects from the top 5 teams in the hackathon. Each project addresses key challenges in AI trustworthiness and innovation.

---

### 🏆 **1st Place: HERMES AI**

**GitHub Repository**: [HERMES AI Implementation](https://github.com/seonglae/emgsd-hermes)  
**Presentation Slides**: [HERMES AI Slides](hackathon-showcases%2FHERMES-AI%2Fslides.pdf)  

**Track**: **Track 2**

#### **Project Description**  
Language models (LLMs), trained on human-produced data, often inherit and propagate harmful stereotypes. HERMES AI uses **Mechanistic Interpretability** to mitigate such issues by training a Sparse Autoencoder (SAE) on the **Expanded Multi-Grain Stereotype Dataset (EMGSD)**. The project demonstrates effective manipulation of GPT-2’s text generation, reducing harmful stereotypes and achieving ethical AI outputs.

---

**Team Members**:  
- **Seonglae Cho**: sungle3737@gmail.com  
- **Gustavo Costa**: gustavo@arcos.org.br  
- **Linnea Loserius**: loserius127@gmail.com  
- **Yung Hsaun Wu**: wu8815@gmail.com  
- **Andrea Lo**: lpsandrea02@gmail.com  

---

### 🥈 **2nd Place: 2 Chill Guys**


**GitHub Repository**: *Will update shortly in the future*  
**Presentation Slides**: *Will update shortly in the future* 

**Tracks**: **Track 1** and **Track 2**

#### **Project Description**  
2 Chill Guys tackled challenges in both tracks with innovative solutions:  

**Track 1**:  
- Utilized **Optuna** to design and optimize custom pipelines for datasets in the HolisticAI library.  
- Focused on balancing **performance** and **fairness** to align with trustworthy AI principles.

**Track 2**:  
- Implemented **DistilBERT** combined with sparse autoencoders to investigate stereotype encoding in language models.  
- Prioritized interpretability and bias analysis, providing insights into stereotype representation and effective mitigation strategies.

---

**Team Members**:  
- **Nichita Mitrea**: andsad52@gmail.com  
- **Anna Aghajanyan**: aghajanyananna03@gmail.com

---

### 🥉 **3rd Place: ARM**

**GitHub Repository**: [ARM Implementation](https://github.com/rk68/holistic-hack)  
**Presentation Slides**: *Will update shortly in the future* 

**Tracks**: **Track 1** and **Track 2**

#### **Project Description**  
ARM developed innovative methods for both tracks by focusing on fairness, accuracy, and sustainability in machine learning models:

**Track 1**:  
1. **Custom Training and Pruning for Tree-Based Models**:  
   - Designed a custom objective function using **HolisticAI's metrics library**.  
   - Incorporated fairness metrics such as disparate impact and equal opportunity into the training process.

2. **Bayesian Optimization**:  
   - Leveraged **Optuna** for hyperparameter search to optimize multiple objectives, including accuracy and fairness.

3. **Pre-Pruning with Fairness Penalty**:  
   - Introduced two custom tree-pruning methods incorporating a fairness penalty.  
   - Reduced systemic gender bias while maintaining accuracy and promoting explainability.  
   - Enhanced carbon efficiency by training a single model with fairness included from the start, avoiding multiple training runs.

This approach demonstrates how FairML techniques can effectively ensure equity, sustainability, and performance in modern AI systems.

---

**Team Members**:  
- **Rishi Kalra**: rishi.kalra.20@ucl.ac.uk  
- **Avanija Menon**: avanijamenon@gmail.com  
- **Murtaza Dhanerawala**: [No email provided]  
---

**Team Members**:  
- **Emily Carter**: emily@example.com  
- **Ahmed Khan**: ahmed@example.com  
- **Sophia Lin**: sophia@example.com  

---

### 🏅 **4th Place: Stery Class**

**GitHub Repository**: [Stery Class Implementation](https://github.com/alexkstern/stery_class_)  
**Presentation Slides**: *Will update shortly in the future* 

**Tracks**: **Track 2**

#### **Project Description**  
Stery Class focused on developing a sustainable, high-performance classification pipeline with a two-stage approach for stereotype classification:

**Track 2**:  
1. **Two-Stage Classification Pipeline**:  
   - **Stage 1**: Utilized a **LightGBM classifier** with **TF-IDF vectorization** and innovative features like cosine similarity between input text and mean sentence embeddings for stereotype classes.  
   - **Stage 2**: Predicted category (stereotype-related or unrelated) by augmenting Stage 1 features with class probabilities from the first model’s forward pass.

2. **Focus on Sustainability**:  
   - Prioritized lightweight and efficient inference, ensuring reduced environmental impact without compromising accuracy.

3. **Inspiration from Generative Models**:  
   - Proposed a generative model framework using **Llama 3 8B with LoRA** for coarse-to-fine stereotype classification and reasoning. While computational constraints prevented real-time implementation, the pipeline design drew inspiration from this generative model structure.

This efficient yet innovative approach highlights the potential for combining lightweight ML models with ideas from generative AI to achieve interpretability, efficiency, and sustainability.

---

**Team Members**:  
- **Alexander Stern**: alexander.stern.20@ucl.ac.uk  
- **Jose Caceres**: jose.valenzuela.24@ucl.ac.uk  
---

### 🎖 **5th Place: Holistic Indians**

**GitHub Repository**: *Will update shortly in the future*  
**Presentation Slides**: *Will update shortly in the future*

**Tracks**: **Track 1** and **Track 2**

#### **Project Description**  
Holistic Indians approached both tracks with a focus on mitigating biases, ensuring privacy, and prioritizing sustainability in stereotype classification tasks:

**Track 2**:  
- **Bias Mitigation**:  
   - Addressed bias in race stereotypes within text data by generating synthetic data to counter sampling bias.  
   - Introduced regularization techniques to enhance model generalization and fairness.  

- **Privacy and Sustainability**:  
   - Incorporated considerations for privacy to protect sensitive data during model training and deployment.  
   - Focused on environmental sustainability by adopting resource-efficient methods in their implementation.

This solution underscores the importance of fairness, privacy, and environmental responsibility in modern AI systems.

---

**Team Members**:  
- **Vignesh Balaji**: guruvignesh2001@gmail.com  
- **Vishal Sharma**: Vishal2510sharma@gmail.com  
- **Sameeh Razak**: sameehrazak366@gmail.com  
- **Sayak Mukherjee**: sayak.mukherjee20@imperial.ac.uk  
- **Arhaan Mohammed Shaikh**: arhaan18june@gmail.com  
---

**Team Members**:  
- **Oliver Brown**: oliver@example.com  
- **Hana Mori**: hana@example.com  
- **Luis Fernandez**: luis@example.com  

## Track 1: Multi-Objective Optimization for AI Trustworthiness in Tabular Data Classification

### Goal

The goal of this track is to **develop a multi-objective optimization algorithm** that improves the **trustworthiness** of AI models in tabular data classification tasks. Participants will design algorithms to simultaneously optimize:

- **Performance**: Ensure the AI model achieves high accuracy and effectiveness in predicting outcomes based on the dataset provided.

- **Fairness**: Focus on identifying and mitigating systemic biases in AI systems to ensure equitable outcomes for all users across diverse populations.

- **Robustness**: Measure the model’s ability to perform reliably under varied scenarios, including generalization, adaptability, and resistance to adversarial conditions.

- **Privacy**: Protect data and systems from unauthorized access, misuse, or threats to confidentiality and integrity.

- **Security**: Strengthen the AI system's defense against vulnerabilities and unauthorized access to ensure its safe use in real-world applications.

- **Explainability**: Emphasize understanding and interpreting model decisions, fostering trust and accountability through clear reasoning pathways.

- **Sustainability**: Examine the resource impact of AI systems, including energy efficiency, carbon footprint, and their societal and regulatory implications.


## Track 2: Building Trustworthy Models for Stereotype Classification in Text Data


### Goal

The goal of this track is to build **ethical and trustworthy AI systems** for detecting stereotypes in text data. Participants will work with the **Expanded Multi-Grain Stereotype Dataset (EMGSD)** to classify text as:
- Containing **stereotypes**
- Being **neutral**
- Being **unrelated**

Participants can start with methods from the **HEARTS framework** outlined in the following paper: [HEARTS Framework Paper](https://arxiv.org/abs/2409.11579)


The track also emphasizes addressing key ethical considerations:

- **Performance**: Ensure the AI model achieves high accuracy and effectiveness in predicting outcomes based on the dataset provided.

- **Fairness**: Focus on identifying and mitigating systemic biases in AI systems to ensure equitable outcomes for all users across diverse populations.

- **Robustness**: Measure the model’s ability to perform reliably under varied scenarios, including generalization, adaptability, and resistance to adversarial conditions.

- **Privacy**: Protect data and systems from unauthorized access, misuse, or threats to confidentiality and integrity.

- **Security**: Strengthen the AI system's defense against vulnerabilities and unauthorized access to ensure its safe use in real-world applications.

- **Explainability**: Emphasize understanding and interpreting model decisions, fostering trust and accountability through clear reasoning pathways.

- **Sustainability**: Examine the resource impact of AI systems, including energy efficiency, carbon footprint, and their societal and regulatory implications.