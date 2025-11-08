# 🎬 AI - Movie Recommendation System

> Discover your next favorite movie with **AI-powered recommendations** — sleek, smart, and built for movie lovers.

<p align="center">
  <img src="https://github.com/usmanamin3254/ai-movie-recommendation-System/blob/main/Screenshot 2025-11-08 220639.png?raw=true" alt="AI Movie Recommender Preview" width="800"/>
</p>

---

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python 3.10+"></a>
  <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/Framework-Streamlit-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit"></a>
  <a href="https://www.themoviedb.org/documentation/api"><img src="https://img.shields.io/badge/API-TMDb-01B4E4?logo=themoviedatabase&logoColor=white" alt="TMDb API"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License"></a>
  <a href="https://github.com/usmanamin3254/ai-movie-recommendation-System/stargazers"><img src="https://img.shields.io/github/stars/usmanamin3254/ai-movie-recommendation-system?style=social" alt="GitHub Stars"></a>
</p>

---

## 🚀 Getting Started

<p align="center">
  <kbd>
    <img src="https://img.shields.io/badge/Clone%20Repo-Git-blue?logo=git&logoColor=white" alt="Clone Repo"/>
    &nbsp;
    <img src="https://img.shields.io/badge/Install-Python-green?logo=python&logoColor=white" alt="Install Python"/>
    &nbsp;
    <img src="https://img.shields.io/badge/Run-App-Streamlit-orange?logo=streamlit&logoColor=white" alt="Run App"/>
  </kbd>
</p>

1. **Clone the repository**  
```bash
git clone https://github.com/usmanamin3254/ai-movie-recommendation-system.git
cd ai-movie-recommender
(Optional) Set up a virtual environment

bash
Copy code
python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\Scripts\activate
Install dependencies

bash
Copy code
Run the app

bash
Copy code
streamlit run app.py
Open the URL provided by Streamlit in your browser. Done! 🎉

✨ Feature Highlights
<p align="center"> <table> <tr> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Recommendations" alt="Smart Recommendations" width="200"/><br> <b>Smart Movie Recommendations</b><br>Top 5 AI-powered suggestions </td> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Movie+Details" alt="Movie Details" width="200"/><br> <b>Rich Movie Details</b><br>Posters, ratings, genres, overview </td> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Live+Integration" alt="TMDb Integration" width="200"/><br> <b>Live TMDb Integration</b><br>Always up-to-date movie info </td> </tr> <tr> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Responsive+UI" alt="UI Design" width="200"/><br> <b>Sleek UI</b><br>Gradient styling & hover effects </td> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Fast+Performance" alt="Performance" width="200"/><br> <b>Optimized Performance</b><br>Cached results for faster loads </td> <td align="center"> <img src="https://via.placeholder.com/200x300.png?text=Error+Handling" alt="Error Handling" width="200"/><br> <b>Error Handling</b><br>Gracefully manages missing movies or API issues </td> </tr> </table> </p>
🧠 Tech Stack
Component	Technology
Language	Python 3.10+
Framework	Streamlit
API	TMDb (The Movie Database)
Libraries	requests, pandas, pickle
Storage	Precomputed similarity matrix (similarity.pkl)

⚙️ Prerequisites
🐍 Python 3.10+

🔑 TMDb API Key (keep it private in app.py)

📂 movie_list.pkl & similarity.pkl in project root

🔍 How It Works

Select or search for a movie.

Click “Get Recommendations.”

Explore the Top 5 recommended movies, complete with:

🎞️ Poster

⭐ Rating

📆 Release Year

🎭 Genres

🧾 Overview

🧩 Project Structure
bash
Copy code
ai-movie-recommender/
│
├── app.py                         # Main Streamlit application
├── Notebook.ipynb                 # Builds movie dataset & similarity matrix
├── movie_list.pkl                 # Movie metadata
├── similarity.pkl                 # Precomputed similarity matrix           
├── assets/
│   └── ai_movie_recommender_preview.png
└── README.md
🎨 Customization
Feature	How to Modify
TMDb API Key	Replace TMDB_API_KEY in app.py
Dataset	Update or rebuild using Notebook.ipynb
UI Styling	Adjust CSS in Streamlit section

⚠️ Limitations
Recommendations rely on a precomputed similarity matrix

TMDb API rate limits apply

Requires local .pkl files to function correctly

📄 License
MIT License © 2025
Usman Amin (@usmanamin3254)
Project: AI-Movie Recommendation System
