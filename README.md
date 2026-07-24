# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Streamlit**, and **Machine Learning**. The application recommends similar movies based on the selected movie and displays their posters using the TMDB API.

## 🚀 Demo

You can deploy this project using Streamlit Community Cloud.

## 📌 Features

- 🎥 Recommend top 5 similar movies
- 🖼️ Fetch movie posters using TMDB API
- ⚡ Fast recommendations using precomputed similarity matrix
- 🌐 Interactive web interface built with Streamlit
- 📱 Responsive and user-friendly UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- Scikit-learn
- Pickle
- Requests
- Gdown
- TMDB API

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│
├── app.py
├── movie_dict.pkl
├── similarity.pkl (Downloaded automatically)
├── requirements.txt
├── Procfile
├── setup.sh
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### Create virtual environment (Optional)

```bash
python -m venv venv
```

Activate the environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

## 📸 Application Preview

- Select a movie from the dropdown.
- Click **Recommend**.
- Get the top 5 recommended movies along with their posters.

---

## 🧠 How It Works

1. User selects a movie.
2. The application finds its index in the dataset.
3. The similarity matrix is used to calculate similar movies.
4. Top 5 recommendations are selected.
5. Posters are fetched dynamically using the TMDB API.

---

## 📊 Dataset

The project uses the **TMDB 5000 Movies Dataset** available on Kaggle.

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## 🔑 TMDB API

Movie posters are fetched using the TMDB API.

Get your API key from:

https://www.themoviedb.org/

---

## 📦 Deployment

This project can be deployed on:

- Streamlit Community Cloud
- Render
- Railway

---

## 👨‍💻 Author

**Abhishek Mishra**

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-linkedin

---

## ⭐ Future Improvements

- Hybrid Recommendation System
- Search by Genre
- Movie Details Page
- User Authentication
- Watchlist Feature
- IMDb Ratings Integration

---

## 📄 License

This project is licensed under the MIT License.

---

### ⭐ If you found this project useful, don't forget to star the repository!
