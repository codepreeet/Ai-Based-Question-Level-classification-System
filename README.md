# Final Year Project — AI-Based Question Level Classification System

## Project Title
AI-Based Question Level Classification System Using Traditional NLP (TF-IDF + SVM)

## About This Project
This is my final year major project for the completion of my undergraduate degree.
I, Gurpreet Singh, am the group leader of this project.

**Objective:** Develop an intelligent text classification system that automatically assigns:
- Difficulty Level (Easy, Moderate, Hard)
- Bloom’s Taxonomy Level (L1–L6)
to a large set of educational questions.

## Key Highlights
- **Dataset:** 8500+ unique questions collected, cleaned, and verified for duplicates.
- **Approach:** Pure traditional NLP — no deep learning.
- **Vectorization:** TF-IDF encoding.
- **Classifier:** Support Vector Machine (SVM) for multi-label classification.
- **Performance:** High accuracy through careful feature engineering.
- **Tools Used:** Python, scikit-learn, pandas, matplotlib.

## Project Structure

| File/Folder | Description |
| ----------- | ------------ |
| Final_Year_Project.ipynb | Jupyter Notebook with full code for preprocessing, training, evaluation, and visualization. |
| data/ | Folder for the cleaned dataset CSVs. |
| results/ | Plots, confusion matrices, and performance reports. |

## What the Model Does
- Reads raw question text
- Converts text to TF-IDF vectors
- Trains an SVM classifier
- Predicts both Difficulty Level and Bloom’s Taxonomy Level
- Evaluates with accuracy, precision, recall, F1-score
- Visualizes results with confusion matrices and accuracy plots

## How to Run
1. Clone this repository.
2. Open Final_Year_Project.ipynb in Google Colab or Jupyter Notebook.
3. Install required packages:
   pip install -U scikit-learn pandas matplotlib
4. Run the notebook step-by-step to:
   - Load data
   - Preprocess
   - Train the SVM
   - Evaluate and visualize results

## Project Leader
- Name: Gurpreet Singh
- Institution: Haldia Institute of Technology
- Role: Group Leader and Developer of this Final Year Major Project

## License
This project is open for academic and research use. Please cite appropriately.

## Acknowledgements
Special thanks to my faculty guide and the open-source community for scikit-learn, pandas, and matplotlib.

## How to Cite
@project{singh2025finalyear,
  author = {Gurpreet Singh},
  title = {Automated Classification of Question Difficulty and Bloom's Taxonomy Using TF-IDF + SVM},
  year = {2025},
  note = {Undergraduate Final Year Project, Haldia Institute of Technology}
}
