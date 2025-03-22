# 🎬 Movie Recommender System

## 📖 Overview
This project is a **Movie Recommender System** built using **Streamlit** and deployed on **Render**. It suggests top 5 movies similar to the one you select, along with their posters, using content-based filtering techniques and The Movie Database (TMDb) API.

## ✅ Features
- Recommends 5 movies based on user-selected input.
- Displays movie posters using TMDb API.
- Clean, interactive UI built using Streamlit.
- Fully deployed and accessible via Render.

## 🚀 Deployment Link
👉 [Live Demo on Render](https://mrs-rohit.onrender.com/)

## 🛠️ Tech Stack
- Python
- Pandas
- Streamlit
- Pickle (for loading pre-computed data)
- Requests
- TMDb API

## 📂 Project Structure
```
├── app.py                        # Main Streamlit application
├── movie_dict.pkl                # Pickled dictionary of movie data
├── similarity.pkl                # Pickled similarity matrix
├── movie_recommender_system.ipynb # Jupyter notebook with concept explanation
└── README.md                     # Project documentation
```

## 📥 Installation & Setup
1. Clone the repository:
```
git clone https://github.com/rohitnitj/mrs-rohit.git
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the app locally:
```
streamlit run app.py
```

## 🧩 How It Works
- Movie similarity is precomputed and stored in `similarity.pkl`.
- The user selects a movie.
- The app finds the most similar movies using the similarity matrix.
- Fetches posters from TMDb API.
- Displays recommendations and posters side by side.

## 🔑 API Key
- TMDb API is used for fetching movie posters. Replace the placeholder key with your own if needed:
```
https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY&language=en-US
```

## 📓 Concepts Explanation
All the concept explanations and data preparation are documented in the provided Jupyter notebook `movie_recommender_system.ipynb`.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/177b9298-229a-4754-94fb-4fa110fd40c2)
![image](https://github.com/user-attachments/assets/63533a74-3e89-444e-9110-740e2aece2f6)
![image](https://github.com/user-attachments/assets/67bb1004-e3f0-4b31-ade6-f869a0786fb6)


## 📃 License
This project is licensed under the [MIT License](LICENSE).

---
### ⭐ If you like this project, give it a star and share! ⭐

