Resume Screening Application
This project is a Resume Classifier that uses Natural Language Processing (NLP) and Machine Learning (ML) techniques to automatically classify resumes into professional categories.


Project Objective
The primary goal is to demonstrate how machine learning can be applied to real-world HRTech problems, helping automate and accelerate resume screening in the recruitment process.


Features
- Extracts and preprocesses text from resumes
- Uses TF-IDF for feature extraction
- Trains a machine learning classifier on labeled resume data
- Supports multiple resume categories (e.g., Data Science, Web Development, etc.)
- Web app interface using Streamlit or Flask


Project Structure
├── app.py # Main application file
├── ResumeScreeningWithPython.ipynb # Jupyter Notebook with EDA and model training
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── .gitignore # Git ignore rules
├── package.json # Node dependencies (if using frontend tools)
├── package-lock.json
├── .venv/ or node_modules/ # Virtual environment / node modules
├── encoder.pkl # Encoded label file
├── tfidf.pkl # TF-IDF transformer
├── clf.pkl # Trained classifier
└── UpdatedResumeDataSet.csv # Dataset used



Requirements
Install all Python dependencies : pip install -r requirements.txt


How to Run
streamlit run app.py


Model
- TF-IDF for vectorizing resume text
- ML model (e.g., Logistic Regression / Random Forest / XGBoost)
- Evaluation using accuracy, precision, recall


Dataset
The dataset consists of categorized resumes labeled into various job profiles.


Use Case
This application can be used by HR departments and recruiters to speed up the initial screening of resumes, reducing manual effort and ensuring better candidate-job matching.
