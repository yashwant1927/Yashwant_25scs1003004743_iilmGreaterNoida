# Yashwant_25scs1003004743_iilmGreaterNoida
Machine learning spam email classifier built with Python and NLP using a Naive Bayes model. Includes text preprocessing, TF-IDF feature extraction, and precision-recall evaluation to automatically detect and filter spam emails
🚀 Overview
Spam emails waste time, bandwidth and productivity.
This project builds an end-to-end spam detection system that learns from email text and automatically classifies new messages as:
❌ Spam
✅ Ham (Legitimate)
The project is inspired by research on Naive Bayesian Anti-Spam Filtering and implements a complete ML pipeline.
🧠 Features
Text preprocessing using NLP
Stopword removal & Lemmatization
TF-IDF feature extraction
Multinomial Naive Bayes classifier
Precision, Recall & Accuracy evaluation
Command-line prediction script
Modular and beginner-friendly code structure
🛠️ Tech Stack
Category
Tools
Language
Python
ML Library
Scikit-learn
NLP
NLTK
Data Handling
Pandas, NumPy
Model Saving
Joblib
📂 Project Structure

naive-bayes-spam-filter/
│
├── data/                 # dataset folder (ignored in git)
├── models/               # saved trained models
├── notebooks/            # experiments
├── src/                  # source code
│   ├── preprocess.py
│   ├── train_model.py
│   └── predict.py
├── research_paper/
├── requirements.txt
└── README.md
⚙️ Installation
Clone the repository:
Bash
git clone https://github.com/yourusername/naive-bayes-spam-filter.git
cd naive-bayes-spam-filter
Install dependencies:
Bash
pip install -r requirements.txt
▶️ Train the Model
Bash
python src/train_model.py
The trained model will be saved inside the models/ folder.
🔮 Predict New Email
Bash
python src/predict.py "Congratulations! You won a lottery"
Output

SPAM
📊 Model Evaluation
The model is evaluated using:
Accuracy
Precision
Recall
F1-Score
Special focus is given to reducing false positives (important emails marked as spam).
📚 Research Inspiration
Based on research on Naive Bayesian Anti-Spam Filtering and cost-sensitive evaluation techniques.
🌟 Future Improvements
Deep Learning models (LSTM / Transformers)
Web App (Flask/Streamlit)
Gmail API Integration
Real-time spam detection
🤝 Contributing
Contributions are welcome!
Feel free to fork the repo and submit a pull request.
📄 License
This project is licensed under the MIT License
Author 
Yashwant Kumar 
