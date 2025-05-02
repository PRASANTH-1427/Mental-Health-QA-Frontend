## 🧠 Mental Health Questionnaire Web App

A user-friendly web application to assess mental health using standardized questionnaires like PHQ-9 and GAD-7, powered by machine learning (ML) and large language models (LLMs).

## 🚀 Features

Interactive questionnaire built with Streamlit
PHQ-9 and GAD-7 scoring
ML-based prediction and classification
LLM-based reasoning, recommendations, and tips
Backend built with FastAPI
Fully deployed on Render (Free Plan)

## 📌 Tech Stack

- Frontend: Streamlit
- Backend: FastAPI
- Deployment: Render
- Languages: Python
- APIs: ML model predictions + LLM insights

🖥️ Local Setup (Frontend)

```bash

# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```
## Note:-
Make sure your backend (FastAPI) is running locally at:
http://127.0.0.1:8000

or 

Change the backend URL in app.py:
backend_url = "https://your-fastapi-service.onrender.com"

## 🧪 API Endpoints (FastAPI)

Endpoint | Method | Description
/get-questions | GET | Fetch PHQ-9 and GAD-7 questions
/analyze | POST | Submit answers for analysis

## ✅ Example Output
- Scores: PHQ-9: 12, GAD-7: 8
- ML Predictions: SVM, RandomForest, etc.
- LLM Insights:
    - Classification: Moderate depression
    - Reasoning: Based on answers
    - Recommendations: Mindfulness, therapy, etc.
    - Tips: Daily walk, sleep hygiene...