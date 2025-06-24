🎓 Final Year Project — AI-Based Question Level Classification System

📌 Project Title
AI-Based Question Level Classification System Using Traditional NLP (TF-IDF + SVM)

🧑‍🎓 About This Project
This is my Final Year Major Project for the completion of my undergraduate degree.
I, Gurpreet Singh, am the Group Leader of this project.

Objective:
Develop an intelligent text classification system that can automatically assign:

✅ Difficulty Level (Easy, Moderate, Hard)

✅ Bloom’s Taxonomy Level (L1–L6)
to a large set of educational questions.

✅ Key Highlights
📚 Dataset:
8500+ unique questions collected, cleaned, and verified to remove duplicates.

🧩 Approach:
Pure Traditional NLP — no deep learning, only robust classical methods.

✏️ Vectorization:
TF-IDF encoding for each question text.

🧮 Classifier:
Support Vector Machine (SVM) for multi-label classification.

📈 Performance:
High accuracy due to careful feature engineering and dataset curation.

🛠️ Tools Used:
Python, Scikit-learn, Pandas, Matplotlib.

⚙️ Project Structure
File/Folder	Description
Final_Year_Project.ipynb	Jupyter Notebook containing full code for preprocessing, training, evaluation, and visualization.
data/	Folder containing the cleaned dataset CSV files.
results/	Plots, confusion matrices, and performance reports.

📊 What the Model Does
✅ Reads raw question text
✅ Converts text to TF-IDF vectors
✅ Trains an SVM classifier
✅ Predicts both Difficulty Level and Bloom’s Taxonomy Level for unseen questions
✅ Evaluates with Accuracy, Precision, Recall, F1-score
✅ Visualizes results with confusion matrices and accuracy plots

🚀 How to Run
1️⃣ Clone this repository
2️⃣ Open Final_Year_Project.ipynb in Google Colab or Jupyter Notebook
3️⃣ Install required packages:

bash
Copy
Edit
pip install -U scikit-learn pandas matplotlib
4️⃣ Run the notebook step-by-step to:

Load data

Preprocess

Train the SVM

Evaluate and visualize results

👨‍🎓 Project Leader
Name: Gurpreet Singh

Institution: Haldia Institute of Technology

Role: Group Leader and Developer of this Final Year Major Project

📜 License
This project is open for academic and research use. Please cite appropriately if used.

✨ Acknowledgements
My respected faculty guide and project mentor

The open-source community for scikit-learn, pandas, and matplotlib

📌 Contact
For any queries or collaboration ideas, feel free to open an Issue or connect via my GitHub profile.

📎 How to Cite
@project{singh2025finalyear,
  author = {Gurpreet Singh},
  title = {Automated Classification of Question Difficulty and Bloom's Taxonomy Using TF-IDF + SVM},
  year = {2025},
  note = {Undergraduate Final Year Project, Haldia Institute of Technology}
}
⭐️ If you find this project useful, please star this repository!
