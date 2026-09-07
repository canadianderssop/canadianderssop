# Functional Network Classifier

This branch contains the development pipeline, matching engine, and evaluation frameworks for the functional network classifier project. It uses existing brain atlases to identify and classify functional network atoms outputted by the SPARK pipeline (https://pubmed.ncbi.nlm.nih.gov/27046111/).

---

## 1. Project Report
For a comprehensive analysis of the methodology, experimental design, and full statistical results, please refer to the complete project documentation:

📂 **[Read the Full Project Report](COMP_401_Final_Report-7-2.pdf)** 

---

## 2. Notebook Overview (`network_classv8.ipynb`)
The primary execution environment for this branch is `network_classv8.ipynb`. The workflow within the notebook is structured as follows:

1. **Brain Atlas Import:** Loading atlases used using NiLearn.
2. **Atom Import:** Loading every atom stored on a local drive.
3. **Model Architecture:** Spatial correlation engine.
4. **Evaluation & Visualization:** Generating confusion matrices, visualizing misidentified networks.

---

## 3. Quick Start & Environment Setup

To run the notebook interactively with all dependencies configured, click the badge below:

[![Open In Colab](https://drive.google.com/file/d/1P6O222bmIqURKvus3Afp8_MFMo_9Cnug/view?usp=sharing)](https://drive.google.com/file/d/1P6O222bmIqURKvus3Afp8_MFMo_9Cnug/view?usp=sharing)


## 4. Dependencies
* **Core Libraries:** `numpy`, `pandas`, `nilearn`, `sklearn`, `matplotlib`, `seaborn`.
