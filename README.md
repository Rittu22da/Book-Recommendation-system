# Book-Recommendation-system
A smart and interactive Book Recommendation System built using Machine Learning, Collaborative Filtering, and a Flask web interface for real-time recommendations.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b502005c-56ba-44c2-afe3-f99974716893" />
<img width="803" height="519" alt="image" src="https://github.com/user-attachments/assets/3069f989-f1f8-4cd6-b282-7f44779dbcc0" />

🚀 Features

🔍 Top Trending Books based on popularity

🤝 Collaborative Filtering to suggest books users may like

🧠 Uses a trained ML model & processed rating datasets

🌐 Simple & responsive Flask web app

⚡ Fast loading with pre-computed pickle files

🖼️ Displays book covers, author, ratings & vote count

🛠️ Tech Stack

Python

Flask (for backend server)

Pandas, NumPy

Pickle (for serialized ML objects)

HTML / CSS

Jupyter Notebook (model training & data preprocessing)

📂 Project Structure
├── app.py                  # Flask application :contentReference[oaicite:1]{index=1}
├── popular.pkl             # Pickle file with precomputed book popularity
├── book_system.ipynb       # Notebook for training & EDA
├── templates/
│   └── index.html          # Frontend UI
└── static/
    └── style.css           # Stylesheet (optional)

⚙️ How It Works

Data Preprocessing

Cleaned dataset

Removed duplicates

Calculated:

Average Rating

Number of Ratings

Popular Books Dataset

Model Building

Used Collaborative Filtering (KNN)

Created similarity matrix

Stored processed objects as .pkl

Web App
The Flask app loads popular.pkl and renders top book recommendations.
