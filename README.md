📩 Spam Message Detector

An end-to-end Machine Learning web application that detects whether a text message is Spam or Not Spam (Ham) using Natural Language Processing (NLP) and a Multinomial Naive Bayes classification algorithm.
The application is built using Python, Scikit-Learn, NLTK, and Streamlit, providing a simple and interactive interface for real-time spam message detection.

🌟 Features

- Spam Detection: Classifies messages as Spam or Not Spam (Ham).
- Real-Time Prediction: Provides instant classification results.
- Confidence Score: Displays prediction probability (if supported by the trained model).
- Text Preprocessing: Converts text to lowercase, tokenizes words, removes stopwords and punctuation, and applies stemming.
- Interactive Interface: User-friendly web application built with Streamlit.
- Machine Learning Model: Uses a trained Multinomial Naive Bayes classifier.

🛠️ Tech Stack

Technology| Purpose
Python| Programming language
Streamlit| Web application interface
Scikit-Learn| Machine learning
NLTK| Natural Language Processing
Pandas| Data manipulation
NumPy| Numerical operations
TF-IDF| Text feature extraction
Multinomial Naive Bayes| Message classification
Pickle| Model serialization

📂 Project Structure

Spam-Message-Detector/
│
├── app.py
├── Spam.ipynb
├── spam.csv
├── MultinomialNBModel.pkl
├── tfidfvectorizer.pkl
├── requirements.txt
└── README.md

File Description

- "app.py" – Main Streamlit application containing the user interface, text preprocessing, and prediction logic.
- "Spam.ipynb" – Notebook containing data analysis, preprocessing, and model training.
- "spam.csv" – Dataset containing spam and legitimate messages.
- "MultinomialNBModel.pkl" – Pre-trained Multinomial Naive Bayes model.
- "tfidfvectorizer.pkl" – Saved TF-IDF vectorizer for converting text into numerical features.
- "requirements.txt" – List of required Python libraries.
- "README.md" – Project documentation.

⚙️ Installation and Setup

1. Clone the Repository
git clone "https://github.com/aasifkhancse/Sms-Spam-Detection.git"

2. Navigate to the Project Directory
cd Spam-Message-Detector

3. Install Dependencies
pip install -r "requirements.txt"

4. Run the Application
streamlit run "app.py"

5. Open the Application
After running the command, open the local URL displayed in your terminal:
http://localhost:8501

🚀 How to Use

1. Launch the Streamlit application.
2. Enter or paste a text message into the input field.
3. Click the Check Message button.
4. The application processes the entered text.
5. View the prediction result: Spam or Not Spam.

🧠 Machine Learning Workflow

1. Data Collection: Load the SMS spam dataset.
2. Data Preprocessing: Clean and normalize text messages.
3. Tokenization: Split messages into individual words.
4. Stopword Removal: Remove commonly used words.
5. Stemming: Reduce words to their root forms using Porter Stemmer.
6. Feature Extraction: Convert text into numerical vectors using TF-IDF.
7. Model Training: Train a Multinomial Naive Bayes classifier.
8. Prediction: Classify new messages using the trained model.

📦 Requirements

The project dependencies are listed in "requirements.txt".

Main libraries:

- streamlit
- scikit-learn
- scipy
- numpy
- pandas
- nltk
- joblib
- threadpoolctl

🔮 Future Improvements

- Improve model accuracy using additional training data.
- Add support for email spam detection.
- Display prediction confidence with visual charts.
- Improve the user interface and user experience.
- Deploy the application to Streamlit Community Cloud.

👨‍💻 Author

Aasif Khan

Machine Learning | Python | Natural Language Processing

📄 License

This project is developed for educational and learning purposes. You are welcome to explore and modify the source code.
