# 🎬 Movie Recommendation System

A content-based movie recommendation system built with Python, Streamlit, and the TMDB (The Movie Database) API.

## 📌 Features
- Recommends top 5 movies based on cosine similarity.
- Fetches real-time movie posters directly using TMDB API.
- Clean and interactive user interface built with Streamlit.

## 🛠️ Tech Stack
- **Frontend / App**: [Streamlit](https://streamlit.io/)
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn (Cosine Similarity, CountVectorizer)
- **API**: TMDB API (for movie posters)

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
cd <YOUR-REPO-NAME>
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv

# Windows (PowerShell)
.\venv\Scripts\Activate.ps1

# Windows (Command Prompt)
.\venv\Scripts\activate.bat

# Linux / macOS
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App
```bash
streamlit run app.py
```
Open [http://localhost:8501](http://localhost:8501) in your browser.

## 📁 Project Structure
```
├── app.py                      # Streamlit application
├── Recommendation_System.ipynb # Data preprocessing & model training
├── movie_dixt.pkl              # Preprocessed movies dictionary
├── similarity.pkl              # Similarity matrix (handled via Git LFS)
├── requirements.txt            # Project dependencies
└── README.md                   # Documentation
```
