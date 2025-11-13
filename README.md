# NLP_Project2
🎓 University FAQ Chatbot

A simple Natural Language Processing (NLP) based chatbot that answers frequently asked questions about a university such as admissions, hostel, fees, exams, library, and placements.

This project was created as part of a university assignment on NLP and Chatbot Development.

🧠 Project Overview

The University FAQ Chatbot uses text preprocessing and similarity-based query matching to find the most relevant answer from a dataset of FAQs. It helps students quickly access university-related information without manual searching.

🚀 Features

✅ Answers student queries (e.g. admission, hostel, exams, library, etc.)
✅ Uses TF-IDF and Cosine Similarity for matching user queries
✅ NLP preprocessing: tokenization, stopword removal, lemmatization
✅ Easy to extend — you can add more questions and answers to the dataset
✅ Can be deployed using Flask or Streamlit

🛠️ Tools & Libraries

Python 🐍

NLTK – for text preprocessing

Scikit-learn – for TF-IDF and cosine similarity

Pandas – for dataset handling

(Optional) Flask / Streamlit – for web deployment

📂 Dataset

The dataset (faq_dataset.csv) contains two columns:

Question – common university queries

Answer – responses for each query

You can modify or add more FAQs to enhance chatbot accuracy.

Example:

Question	Answer
How much is the admission fee?	Admission fee is ₹5000.
How can I apply for a hostel?	Fill the hostel form online at hostel.university.edu.
When will exams start?	Exams will begin in December as per the academic calendar.
⚙️ How It Works

Preprocess all FAQ questions (tokenization, stopword removal, lemmatization).

Vectorize questions using TF-IDF.

Compare the user query with all questions using cosine similarity.

Return the most similar answer based on the highest similarity score.

🧩 Usage (Google Colab)

Open the file Project_NLP.ipynb in Google Colab.

Run all cells sequentially.

When prompted, type your questions in the chat interface.

Type exit to end the chat.

📈 Example Interaction
🎓 Welcome to the University FAQ Chatbot! Type 'exit' to stop.

You: How can I apply for a hostel?
Chatbot: Fill the hostel form online at hostel.university.edu.

You: When will exams start?
Chatbot: Exams will begin in December as per the academic calendar.

You: exit
Chatbot: Goodbye! 👋

💡 Future Enhancements

Integrate BERT embeddings for better semantic understanding

Add multi-language support

Deploy as a Telegram/WhatsApp chatbot

Include voice query recognition

👨‍💻 Author

Name: Vidhit Madaan
Roll No: 2301201179
Section: C
Subject: NLP (Natural Language Processing) Project
