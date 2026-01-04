# medical-chatbot
Medical Chatbot using Machine Learning & NLP

A Medical Chatbot built using Natural Language Processing (NLP) and Machine Learning that provides basic health guidance based on user symptoms.
This project is educational and informational only and does not provide medical diagnosis or treatment.

📌 Project Overview

The Medical Chatbot interacts with users by understanding their health-related queries such as symptoms (fever, cold, headache, etc.) and provides safe, general medical advice.
It uses TF-IDF vectorization and Logistic Regression to classify user intent and respond accordingly.

⚙️ Technologies Used

Python 🐍

Natural Language Processing (NLP)

Scikit-learn

TF-IDF Vectorizer

Logistic Regression

JSON (for dataset)

Jupyter Notebook

📂 Project Structure
Medical_Chatbot/
│
├── medical_chatbot.ipynb       # Training & chatbot execution
├── medical_intents.json        # Dataset (intents & responses)
├── chatbot_model.pkl           # Trained ML model
├── vectorizer.pkl              # TF-IDF vectorizer
├── label_encoder.pkl           # Encoded labels
└── README.md                   # Project documentation

🧠 How the Chatbot Works

User enters a message (e.g., “I have fever”)

Text is preprocessed (lowercase, cleaned)

TF-IDF converts text into numerical features

ML model predicts the intent

Chatbot returns a suitable response

If confidence is low, chatbot suggests consulting a doctor

🔐 Safety & Ethics

⚠️ Important Notice

This chatbot:

❌ Does NOT diagnose diseases

❌ Does NOT prescribe medicine

✅ Provides general medical guidance only

✅ Advises consulting a medical professional when required

This project is intended only for educational purposes.

▶️ How to Run the Project
Step 1: Install Dependencies
pip install scikit-learn nltk

Step 2: Open Jupyter Notebook
jupyter notebook

Step 3: Run medical_chatbot.ipynb

Run Cell 1 → Train the model

Run Cell 2 → Start the chatbot

💬 Sample Interaction
You: I have fever
Bot: Fever may indicate an infection. Please stay hydrated and rest.

You: Sneezing
Bot: Common cold usually improves with rest and fluids.

You: Chest pain
Bot: ⚠️ This may be an emergency. Please seek immediate medical help.

🎓 Learning Outcomes

Understanding NLP pipelines

Text preprocessing techniques

Intent classification

ML model training & evaluation

Ethical handling of medical data

🚀 Future Enhancements

Add more medical intents & symptoms

Build a web interface using Streamlit

Voice-based medical chatbot

Improve accuracy with larger datasets
