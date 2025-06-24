#Final Year Project — Ai-Based-Question-Level-classification-System
#Project Title - Ai-Based-Question-Level-classification-System Using Traditional NLP (TF-IDF + SVM)

🧑‍🎓 About this Project
This is my final year major project for the completion of my undergraduate degree.
I, Gurpreet Singh, am the Group Leader of this project.
The goal is to develop an intelligent text classification system that can automatically assign:

Difficulty Level (Easy, Moderate, Hard)

Bloom’s Taxonomy Level (L1–L6)

to a large set of educational questions.

✅ Key Highlights
Dataset:
8500+ unique questions collected, cleaned, and verified for duplication.

Approach:
Pure Traditional NLP — no deep learning, only robust classical methods.

Vectorization:
TF-IDF encoding for each question text.

Classifier:
Support Vector Machine (SVM) for multi-label classification.

Performance:
High accuracy achieved due to careful feature engineering and dataset curation.

Tools Used:
Python, sklearn, pandas, matplotlib.

⚙️ Project Structure
File/Folder	Description
Final_Year_Project.ipynb	Jupyter Notebook containing the full code for preprocessing, training, evaluation, and visualization.
data/	Folder for storing the cleaned dataset CSVs.
results/	Plots, confusion matrices, and performance reports.

📊 What the Model Does
Reads raw question text.

Converts text to TF-IDF vectors.

Trains an SVM classifier.

Predicts both Difficulty Level and Bloom’s Taxonomy Level for unseen questions.

Evaluates with metrics: Accuracy, Precision, Recall, F1-score.

Visualizes results with confusion matrices and accuracy plots.

🚀 How to Run
Clone this repository.

Open Final_Year_Project.ipynb in Google Colab or Jupyter Notebook.

Install required packages:

bash
Copy
Edit
pip install -U scikit-learn pandas matplotlib
Run the cells step-by-step to:

Load data

Preprocess

Train the SVM

Evaluate and visualize results

🎓 Project Leader
Name: Gurpreet Singh
Institution: Haldia Institute of Technology
Role: Group Leader and Developer of this Final Year Major Project.

📜 License
This project is open for academic and research use. Please cite appropriately.

✨ Acknowledgements
Faculty guide and project mentor.

Open-source community for scikit-learn and pandas.

📌 Contact
For any queries or collaboration ideas, feel free to reach out via GitHub issues.

✅ Final Note
This repository represents my complete and final implementation.
No deep learning was used — only TF-IDF + SVM, carefully tuned for the best performance on my custom question dataset.

📎 How to Cite
@project{singh2025finalyear,
  author = {Gurpreet Singh},
  title = {Automated Classification of Question Difficulty and Bloom's Taxonomy Using TF-IDF + SVM},
  year = {2025},
  note = {Undergraduate Final Year Project, Haldia Institute of Technology}
}
⭐️ If you find this useful, please star this repo!










This project implements an automated system for classifying the difficulty level and Bloom's Taxonomy level of exam questions using a traditional NLP approach. A dataset of over 1000 unique questions across Math, GK, Programming, and Computer Science was curated and preprocessed. Each question is converted to a TF-IDF vector and classified using a Support Vector Machine (SVM) model. The system achieves high accuracy, demonstrating that classical NLP models remain robust for small to medium datasets. This work supports automated question bank tagging, mock test systems, and intelligent tutoring.
