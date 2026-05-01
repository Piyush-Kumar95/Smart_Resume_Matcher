# Smart Resume Matcher
A Streamlit-based web application that analyzes how well a resume matches a given job description using Natural Language Processing (NLP) techniques.

# 🚀 Features
- 📤 Upload Resume (PDF)
- 📝 Paste Job Description
- 🔍 Text Processing using NLP
- 📊 Match Score using TF-IDF + Cosine Similarity
- 📈 Visual Match Percentage Bar

# 🛠️ Tech Stack
- Python
- Streamlit
- Scikit-learn
- NLTK
- PyPDF2

# 🧠 How It Works
- Extract text from uploaded resume (PDF)
- Clean and preprocess text (tokenization, stopword removal)
- Convert text into numerical vectors using TF-IDF
- Calculate similarity using Cosine Similarity
- Display match score and visualization
