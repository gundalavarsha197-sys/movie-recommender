🎬 Movie Recommendation System

A simple Machine Learning web application that recommends movies based on user selection using Content-Based Filtering (TF-IDF + Cosine Similarity).

📌 Step 1: Project Overview
This project recommends movies similar to the one selected by the user. It uses Machine Learning techniques to analyze movie genres/descriptions and find similarities.

✨ Step 2: Features
🎯 Recommend similar movies
🔍 Search and select any movie
⚡ Fast and lightweight system
🌐 Simple Flask web interface
🧠 Uses ML-based similarity algorithm

🧠 Step 3: How It Works
Movie data is loaded from a dataset (movies.csv)
Text data (genre/description) is converted into vectors using TF-IDF
Cosine similarity is used to measure similarity between movies
Top similar movies are recommended to the user

🛠️ Step 4: Tech Stack
Python 🐍
Flask 🌐
Pandas 📊
Scikit-learn 🤖
HTML / CSS 🎨

📁 Step 5: Project Structure
movie-recommender/
│
├── app.py                 # Main Flask application
├── movies.csv             # Dataset
├── templates/
│   └── index.html         # Frontend UI
├── static/
│   └── style.css          # CSS styling (optional)
└── README.md

⚙️ Step 6: Installation
1. Clone the repository
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
3. Install dependencies
pip install flask pandas scikit-learn

▶️ Step 7: Run the Project
python app.py

🌐 Step 8: Open in Browser

After running the project,
open:http://127.0.0.1:5000/

🎯 Step 9: Example Output

Input: Avengers

Output:
Iron Man
Spider Man
Thor
Batman Begins
# Screenshots
<img width="1918" height="1078" alt="movie" src="https://github.com/user-attachments/assets/81bbddd1-4d62-433c-bd00-49eb17cee350" />


🚀 Step 10: Future Improvements
Add real dataset (MovieLens / TMDB)
Show movie posters using API
Improve recommendation accuracy
Deploy online (Render / Railway)

👨‍💻 Step 11: Author
Name: GUNDALA VARSHA
GitHub: https://github.com/gundalavarsha197-sys/movie-recommender.git
LinkedIn: https://www.linkedin.com/in/gundala-varsha-25a604386/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BVmLugi9VQkay6AxO8GzRNg%3D%3D
