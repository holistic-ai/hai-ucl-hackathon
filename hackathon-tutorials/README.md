<h1 align="center">
<img src="logo.png" width="300">
<br>
Holistic AI x UCL AI Society Hackathon 2024
</h1>

Website: [Holistic AI UCL Hackathon](https://hackathon.holisticai.com/)

Welcome to the **Holistic AI x UCL AI Society Hackathon 2024**! This repository contains all the code, datasets, and resources needed to participate. Whether you're a seasoned data scientist or a beginner with no coding experience, we've got you covered.

---

## Need Help?

- **Hackathon Support**:  
  During the event, reach out to mentors and organizers in-person or through the hackathon's official communication channels for help with setup, coding, or clarifications. Our team is here to support you!

- **Join the hackathon’s communication channels**:  
  For live support from mentors during the event, join our Slack community:  
  [Holistic AI Community Slack](https://join.slack.com/t/holisticaicommunity/shared_invite/zt-2jamouyrn-BrMfeoBZIHT8HbLzB3P9QQ)

---

## No Python? No Problem!

If you do not have Python installed or are unfamiliar with it, don't worry! You can still participate in the hackathon by following one of these options:


### Option 1: Run Jupyter Notebooks Online with Google Colab

Google Colab allows you to run Python code directly in your browser without installing anything on your computer. Here's how:

1. **Visit Google Colab**:  
   Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook File**:  
   - Click on "File" > "Upload Notebook."
   - Select the `.ipynb` file from this repository that you want to work on.

3. **Run the Notebook**:  
   - Follow the instructions provided in the notebook.
   - Execute each code cell step by step by pressing `Shift + Enter`.


### Option 2: Install Python Locally

If you want to run the notebooks on your own machine, follow these steps to install Python and set up your environment:

1. **Download Python**:  
   Visit the [Python official website](https://www.python.org/downloads/) and download the latest version of Python (3.10 or higher).  
   - For Windows: Download the installer and ensure you check the box that says "Add Python to PATH" during installation.  
   - For Mac: Download the installer and follow the setup instructions.  
   - For Linux: Use your package manager (e.g., `sudo apt install python3`).


2. **Install pip**:  
   pip is Python's package manager and is usually included with Python installations. To check if pip is installed, run:
   ```bash
   pip --version
   ```
   If pip is not installed, follow the instructions [here](https://pip.pypa.io/en/stable/installation/).


3. **Install Jupyter Notebook**:

   Once Python and pip are set up, you can install Jupyter Notebook by running the following command in your terminal or command prompt:
   
   ```bash
   pip install notebook
   ```

---

### If you're new to Python, we recommend exploring these beginner-friendly resources:
  - [Google's Python for Beginners](https://developers.google.com/edu/python/)  
    A step-by-step guide to understanding the basics of Python programming.
  - [Google Colab Guide](https://colab.research.google.com/notebooks/intro.ipynb)  
    Learn how to use Google Colab to run Python code in the cloud without any installation.
  - [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/index)  
    Explore tutorials and examples to understand how to work with state-of-the-art machine learning models.


---

## Next: Choose Your Hackathon Track


Once you have Python and pip installed, you are ready to begin the hackathon! You will now select one of the two tracks below based on your interest and skill level. If you have the time and capability, feel free to explore both tracks to maximize your learning and contributions.

   


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

### Approach Options

1. **Utilize the Holistic AI Open-Source Library**:
   - Use the library to measure and mitigate AI risks effectively.
     - [Example Notebooks](https://holisticai.readthedocs.io/en/latest/gallery/index.html)
     - [GitHub Library Link](https://github.com/holistic-ai/holisticai)
     - [Documentation](https://holisticai.readthedocs.io/en/latest/)

2. **Define Custom Metrics and Mitigation Methods**:
   - Tailor your approach by defining novel metrics and mitigation strategies based on the specific dataset and tasks provided.

### Tutorials and Datasets 

To get started, choose one of the three datasets provided below and follow the tutorial tailored to your selected dataset. Each tutorial includes a step-by-step Jupyter Notebook to guide you through the analysis and the development of a multi-objective optimization algorithm.

- [**Bank Marketing Dataset**](track1_multi_objective_optimization/Bank_Dataset.ipynb):  
  Learn how to predict whether a client will subscribe to a term deposit based on features like age, job type, and marital status.

- [**Minimum Wage Dataset**](track1_multi_objective_optimization/Minimum_Wage_Dataset.ipynb):  
  Explore the challenge of predicting whether a worker's income is above or below five times the minimum wage threshold.

- [**Compas Dataset**](track1_multi_objective_optimization/Compas_Dataset.ipynb):  
  Tackle the task of predicting whether a defendant will re-offend within two years using features such as age, prior offenses, and risk scores.

Each dataset offers a distinct problem to solve, and the tutorials are designed to help you create optimization algorithms that enhance trustworthiness in AI systems.

---

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


### Approach Options

1. **Flexibility in Granularity**:
   - Choose your granularity level: sentence-level, token-level, dialogue-level, or define your own custom approach.

2. **Flexibility in Tasks**:
   - Select from various tasks such as binary classification, multi-class classification, multi-label classification, named entity recognition (NER), or propose your own task setup.

3. **Custom Models & Metrics**:
   - Use pre-defined models or build your own. Define novel metrics for stereotype detection and trustworthiness assessment.

4. **Trustworthiness Focus**:
   - Incorporate methods to ensure fairness, explainability, robustness, and privacy, adhering to ethical AI principles.


### Tutorials and Datasets 

To begin, start with the **Main Text Stereotype Detection Tutorial**, which provides a detailed guide to building trustworthy models for detecting stereotypes in text data. If you are interested in enhancing the dataset, two optional tutorials are available that focus on **data augmentation** through scraping or generating additional data.

- [**Main Text Stereotype Detection**](track2_text_stereotype_classification/Main_Text_Stereotype_Detection.ipynb):  
  Dive into classifying text in the EMGSD dataset as containing stereotypes, neutral, or unrelated. This tutorial emphasizes building a robust and ethical classifier while addressing key aspects such as fairness and explainability.

- [**Scraping Biased Data**](track2_text_stereotype_classification/Extra_Scraping_Biased_Data.ipynb) (Optional):  
  Learn how to scrape and preprocess biased text data from online sources. This tutorial helps you enrich the EMGSD dataset with real-world examples, making it more comprehensive.

- [**Generate Biased Data**](track2_text_stereotype_classification/Extra_Generate_Biased_Data.ipynb) (Optional):  
  Fine-tune a biased GPT-2 model to generate stereotype-related text. This generated data can be used to augment the EMGSD dataset for additional experiments and improved results.

Begin with the **Main Text Stereotype Detection Tutorial**, and if time and interest permit, explore the optional tutorials to experiment with data augmentation techniques and enhance the dataset further.

---

## How to Start with?

Now that you've chosen your track and have an idea of the tutorials available, here’s how you can get started with the coding part. Whether you’re new to Python or an experienced programmer, we’ve got options to suit your needs.

1. **Open Google Colab**:  
   Visit [Google Colab](https://colab.research.google.com/).

2. **Upload a Notebook**:  
   - Click on "File" > "Upload Notebook" in Colab.
   - Select the `.ipynb` file from this repository that you want to work on.

3. **Follow the Instructions**:  
   - Execute each cell step by step in the notebook.
   - Colab runs everything in the cloud, so you don’t need to install anything locally.

---

### Option 2: Run Locally (For Participants with Python Installed)

1. **Clone the Repository**:  
   Download the repository to your local machine:
```bash
git clone https://github.com/holistic-ai/hai-ucl-hackathon.git
```

2.	**Navigate to the Repository**:
Open the folder where the repository is stored:

```bash
cd hai-ucl-hackathon
```

3.	**Install Dependencies**:
Ensure you have Python 3.10+ installed, then install the required packages:

```bash
pip install -r requirements.txt
```

4.	**Open the Notebook**:
   Launch Jupyter Notebook and navigate to the tutorial you want to work on:
   
```bash
jupyter notebook track1_multi_objective_optimization/Bank_Dataset.ipynb
```


---

## Submission Guidelines

To ensure a smooth evaluation process, all teams are required to upload their **presentation slides** and any **supporting materials** before their scheduled presentation. Follow the steps below for submission.

---

### Submission Instructions:

- **What to Submit**:
  - Your **presentation slides** in PDF or PPT format.
  - Any supporting materials such as code, diagrams, or additional documentation.

- **How to Submit**:
Use the following Google Form link:  
     [Submission Form](https://forms.gle/dS9hWonvMEbvjCwi9)



### Deadline:

- **Ensure all submissions are completed before your scheduled presentation time**. Late submissions may not be accepted, so please plan ahead.


### Notes:

1. **Late Submissions**:  
   Submissions after the deadline may not be evaluated.

2. **Organization**:  
   Materials should be well-organized and clearly labeled to facilitate evaluation by the judging panel.

3. **Compatibility**:  
   Ensure files are in a standard format (e.g., PDF for slides) and can be easily accessed by the judges.


By following these guidelines, you will ensure that your work is effectively evaluated by the judging panel. If you face any issues during submission, please contact the hackathon organizers immediately.

---



## Team Presentation Guidelines

As part of the hackathon, each team will present their solution to the judging panel. Below are the details and structure to guide you in preparing an impactful presentation.

### Presentation Details:
- **Date and Time**: November 24, 15:00 - 16:30  
- **Time Limit**: 5-10 minutes (maximum 10 minutes)
- **Presentation Schedule**: A list of presentation slots and team order will be released before the presentation session.


### Suggested Presentation Structure:

1. **Problem Statement**  
   - Clearly define the issue your solution is addressing.  
   - Provide context by linking it to the track (Track 1 or Track 2) and the specific challenges within the track.

2. **Objectives**  
   - Highlight the specific goals your system aims to achieve.  
   - Clearly state what success looks like for your project (e.g., performance improvement, ethical considerations, innovation).

3. **Solution Overview**  
   - Briefly describe your solution, focusing on its **key features** and **methodology**.  
   - Explain how your approach addresses the problem and achieves the objectives.

4. **System Design**  
   - Include a **diagram** or visual representation of your system's flow, architecture, or methodology.  
   - Ensure it is clear and helps the audience understand the technical implementation.

5. **Value Proposition**  
   - **Business Value**: Highlight the real-world applications and market impact of your solution.  
   - **Academic Value**: Emphasize novelty, methodology, or potential research contributions.

6. **Risk Considerations**  
   - Address potential risks across the following verticals:
     - **Performance**
     - **Fairness**
     - **Robustness**
     - **Privacy**
     - **Security**
     - **Explainability**
     - **Sustainability**  
   - Briefly describe how your solution mitigates these risks or factors them into its design.

7. **Future Work and Limitations**  
   - Summarize the project and its outcomes.  
   - Highlight future work that could enhance your solution.  
   - Be transparent about any limitations or areas for improvement.

### Additional Tips:
- **Practice Timing**: Ensure your presentation fits within the 5-10 minute time limit.  
- **Engage Your Audience**: Keep your slides and visuals clean and concise. Focus on delivering your points with clarity.  
- **Team Collaboration**: Assign parts of the presentation to different team members to showcase your teamwork.  
- **Prepare for Questions**: Anticipate questions from the judges and be ready to explain your methodology or decisions in detail.

By following this structure and focusing on clear communication, your team will be well-prepared to deliver a compelling presentation to the panel. Good luck!

---

## Marking Criteria

Your presentation will be judged based on the following criteria:

1. **Sustainability (20%)**  
   - Evaluation of the project’s impact on environmental, economic, and social factors.  
   - Focus on energy efficiency, resource optimization, and alignment with ethical principles.

2. **Technical Solidity (20%)**  
   - Demonstration of engineering skills, quality, and efficiency of the implementation, logic, and code.

3. **Presentation Clarity & Design (20%)**  
   - Clarity of written and oral presentation, including visual organization and storytelling effectiveness.

4. **Method Novelty & Creativity (20%)**  
   - Originality and innovation in the approach or methodology, showcasing out-of-the-box thinking and novel solutions.

5. **Business Value (20%)**  
   - Relevance to real-world problems, addressing customer or user needs, and the potential for the solution to develop into a viable business idea.

---

## Judging Panel

Your presentation will be evaluated by the following judges:

- **Holistic AI Team**  
  Experts from Holistic AI specializing in trustworthy AI systems.

- **UCL AI Society**  
  Representatives from the UCL AI Society who bring academic and technical expertise.

- **Guest Team**  
  An external panel of industry professionals and AI researchers to provide diverse perspectives.

---

## Provisional and Final Ranking

The hackathon evaluation process will involve **provisional rankings** announced at the end of the event and **final rankings** determined after further validation of team submissions. Below are the details for each step:


### Provisional Rankings:

- Provisional rankings will be announced at the end of the hackathon, based on:
  - Team presentations
  - Initial project evaluations by the judging panel


### Final Rankings:

- Rankings will be finalized **after validation** of the implementation and materials uploaded by teams.
- Validation ensures that:
  - Solutions meet the stated requirements and functionality.
  - Submitted code and materials are complete, functional, and aligned with the evaluation criteria.


### Awards and Timelines:

- Final rankings and prizes will be confirmed and communicated **within 10 working days** after the hackathon ends.
- Prizes will be disbursed once the validation process is complete.

### Important:

- **Ensure your submission is complete and functional** to avoid delays or disqualification during validation.
  - Double-check your code, implementation, and materials before submitting.
  - Clearly label and organize all files to facilitate smooth validation by the judging panel.