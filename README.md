
# Sustainability Project Evaluation using Multi-Criteria Decision Making (MCDM)

## Overview
This project evaluates and ranks sustainability projects for a manufacturing company using Python-based Multi-Criteria Decision Making (MCDM) techniques. It helps in strategic decision-making by considering multiple evaluation criteria.

## Objectives
- Evaluate sustainability projects based on various criteria.
- Apply data normalization for fair comparison.
- Calculate project scores using MCDM.
- Rank projects based on their final scores.
- Visualize the results.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Project Structure
```
Sustainability_MCDM_Project/

── sustainability_projects.csv           (Dataset of sustainability projects)
── sustainability_mcdm_analysis.ipynb    (Jupyter Notebook with analysis)
── README.md                             (Project Documentation)
── sustainability_project_scores.png     (Output)
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/mominayas/Sustainability_MCDM_Project.git
cd Sustainability_MCDM_Project
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # (Windows: venv\Scripts\activate)
```

3. Install required libraries:
```bash
pip install pandas scikit-learn matplotlib
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Output
- Normalized data for MCDM analysis.
- Final project scores and ranking.
- Visualization of project scores.

## Dataset Information
The dataset used (`sustainability_projects.csv`) contains sample sustainability project data with criteria like Cost, Environmental Impact, Feasibility, and Strategic Fit for academic demonstration.
