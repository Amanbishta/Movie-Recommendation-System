# Movie-Recommendation-System
A smart Content-Based Movie Recommendation System built with Python and Streamlit. It analyzes movies metadata like genre, overview, cast, and crew to recommend films similar to the one you love. Powered by TF-IDF Vectorization and Cosine Similarity for intelligent, personalized suggestions.
# 🎬 Movie Recommendation System 🍿  
> *A Smart Content-Based Movie Recommender with Streamlit UI*  

Discover your next favorite movie 🎞️ using machine learning!  
This project is a **Content-Based Movie Recommendation System** that suggests movies similar to the one you like — powered by **Python, Scikit-learn, and Streamlit** 🚀  

---

## 🌟 Demo  

🎥 **Live Demo:** [Click Here to Try It](#) *(Add your Streamlit Cloud or Hugging Face Spaces link here)*  

🖼️ **App Preview:**  
<p align="center">
  <img src="assets/demo.gif" alt="App Demo" width="600"/>
</p>

---

## 🧠 How It Works  

1. The app loads a movie dataset 📊  
2. Extracts movie features like **genres**, **keywords**, **overview**, and **cast**  
3. Converts them into numeric form using **TF-IDF Vectorization**  
4. Calculates **Cosine Similarity** between all movies  
5. When a user selects a movie, it recommends the most similar ones 💡  

---

## 🧩 Tech Stack  

| 🛠️ Tool | 💡 Purpose |
|----------|------------|
| 🐍 **Python** | Core programming language |
| 📊 **Pandas / NumPy** | Data analysis & manipulation |
| 🤖 **Scikit-learn** | TF-IDF vectorizer & similarity computation |
| 🖥️ **Streamlit** | Web app frontend |
| 🎞️ **TMDB Dataset** | Movie metadata |

---

## 🚀 Features  

✅ Simple, interactive **Streamlit UI**  
✅ Smart, **content-based recommendations**  
✅ Lightweight & easy to deploy  
✅ Fully open-source and customizable  
✅ Works on any dataset with movie features  

---

## ⚙️ Installation  

Clone the repo and set up your environment 👇  

```bash
# Clone the repository
git clone https://github.com/<your-username>/movie-recommendation-system.git

# Navigate to the folder
cd movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

# Project Structure 
movie-recommendation-system/
│
├── data/                # Movie dataset (CSV)
├── app.py               # Main application file
├── model.ipynb          # Notebook with model building
├── requirements.txt     # Dependencies
└── README.md            # Project description
