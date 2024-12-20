![ASHBoost Banner](https://github.com/Bohamad95q8/AshBoost_NumHackhackathon/blob/main/Image/ASHBoostNumHack2024Analysis%20Kuwait.png)

# ASHBoost PyData Community Analysis - NumHack Hackathon 2024 Analyze Track

Welcome to **ASHBoost's** repository for the NumHack Hackathon 2024.  

[![Open in Colab](https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1AvOwKIHHORKKLl_w3bhTwHoIBBW0maKo?usp=sharing)
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
### Requirements

[![NumPy](https://img.shields.io/badge/NumPy-%23177cce.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![IPython](https://img.shields.io/badge/ipython-%23E5E5E5.svg?style=for-the-badge&logo=python&logoColor=white)](https://ipython.org)
[![PyVis](https://img.shields.io/badge/PyVis-%23009639.svg?style=for-the-badge&logo=python&logoColor=white)](https://pyvis.readthedocs.io/)
[![NetworkX](https://img.shields.io/badge/NetworkX-%23193f74.svg?style=for-the-badge&logo=python&logoColor=white)](https://networkx.org/)
[![Sentence-Transformers](https://img.shields.io/badge/Sentence--Transformers-%23FF5733.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.sbert.net/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![ipywidgets](https://img.shields.io/badge/ipywidgets-%23FFDD44.svg?style=for-the-badge&logo=python&logoColor=black)](https://ipywidgets.readthedocs.io/en/latest/)

---

## Features

- 🧪 **Experiment Notebook**: [Colab Notebook](https://colab.research.google.com/drive/1AvOwKIHHORKKLl_w3bhTwHoIBBW0maKo?usp=sharing)
- 📊 **Visualization Tools**: Interactive dashboards for data exploration.
- ⚙️ **Dependencies**: Python, NumPy, Pandas


Welcome to **ASHBoost's** repository for the NumHack Hackathon 2024. We are participating in the **Analyze Track**, showcasing our solution to analyze and extract insights using innovative techniques.  

---
## Overview
This project demonstrates a proof-of-concept for matching contributors to AI projects using synthetic datasets. The results are analyzed and visualized as directed graphs, providing actionable insights and showcasing relationships between projects and contributors.

---

## How It Works
1. **Datasets**:
   - `AI_Projects_Populated_with_Summary.csv`: Contains project titles, required skills, summaries, and roles.
   - `Contributors_with_Summary.csv`: Contains contributor details, skills, summaries, and GitHub/portfolio links.
2. **Analysis**:
   - Match contributors to projects using SentenceTransformer embeddings and cosine similarity.
   - Generate compatibility scores for skills and project roles.
3. **Visualization**:
   - Use NetworkX and pyvis to create directed graphs showing project-contributor relationships.
   - Include dropdown menus for selecting projects and exploring skills dynamically.

---

## Frameworks and Techniques
### Frameworks
- **SentenceTransformers**: Used to encode textual summaries into embeddings.
- **NetworkX and pyvis**: For graph-based visualization of project-contributor relationships.
- **Pandas and NumPy**: For data preprocessing and analysis.
- **IPython Widgets**: For interactive dropdown menus.

### Techniques
- Embedding generation for semantic similarity.
- Cosine similarity for skill matching.
- Directed graph representation to showcase relationships.

### Dataset
Synthetic datasets were generated to simulate real-world scenarios for proof of concept:
- Projects with required skills, summaries, and roles.
- Contributors with expertise summaries and portfolios.

---

## Findings, Difficulties, and Limitations
### Findings
- Graph visualization effectively highlights relationships and compatibility.
- Dropdown menus provide an intuitive interface for data exploration.

### Difficulties
- Handling diverse skill representations in synthetic data.
- Balancing graph clarity with the number of nodes and edges.
- Giving new comers a chance to work and have experience will be hard.

### Limitations
- Synthetic data lacks the complexity of real-world datasets.
- Matching relies heavily on embeddings and may require real-world calibration.
  

---

## Future Directions
- Incorporate real-world datasets for validation and refinement.
- Implement machine learning-based recommendation systems for matching.
- Scale graph visualizations for larger datasets and communities.
- Building an Application to handle the collecting of data as forms, analyzing the data, the producing the visualization outputs.

---

## Build Instructions
### Dependencies
Install the required libraries:
```bash
pip install -r requirements.txt

## How to Run

Follow these steps to reproduce our results:

1. Clone the repository:
   ```bash
   git clone https://github.com/Bohamad95q8/AshBoost_NumHackhackathon.git
