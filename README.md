<!-- README.md for Hybrid Movie Recommender -->

<h1 align="center">
  🎬 HYBRID MOVIE RECOMMENDER SYSTEM
</h1>
<p align="center">
  <em>Where machine learning meets your movie taste 🍿✨</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Expert-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn" />
  <img src="https://img.shields.io/badge/Surprise-SVD-green?style=for-the-badge" />
</p>

---

## 🔍 Overview

This hybrid recommender blends **content-based filtering** (using TF-IDF + cosine similarity) with **collaborative filtering** (via matrix factorization using SVD) to generate smart, contextual, and personalized movie suggestions. Ideal for Netflix-style recommendation engines.

---

## 🚀 Features

- 🎯 Accurate movie suggestions from hybrid scores
- 🧠 ML-powered recommendations
- 📈 Integrated evaluation metrics
- 🛠️ Easy-to-extend architecture
- 🧰 Designed for production deployment

---

## 🧰 Technologies Used

| Category            | Tools & Libraries                                  |
|--------------------|-----------------------------------------------------|
| Languages          | Python, HTML/CSS (for UI)                          |
| Machine Learning   | Scikit-Learn, Surprise                             |
| NLP & Similarity   | TF-IDF Vectorizer, Cosine Similarity               |
| UI (Optional)      | Streamlit                                          |
| Visualization      | Matplotlib, Seaborn                                |

---

## 🗃️ Project Structure

```bash
📁 HYBRID-MOVIE-RECOMMENDER
│
├── content_filter.py       # TF-IDF + cosine similarity logic
├── collaborative_filter.py # SVD collaborative recommender
├── hybrid.py               # Weighted ensemble of both
├── data/movies.csv         # Movie metadata
├── main.py                 # Streamlit app or CLI
├── requirements.txt
└── README.md
```

---

## 💡 How It Works

- Content-based engine builds a similarity matrix on movie genres, keywords, cast, etc.
- Collaborative engine learns user preferences from ratings via matrix factorization.
- Hybrid engine fuses the two with configurable weights.

---

## 🔧 Installation

```bash
git clone https://github.com/Iammanan07/HYBRID-MOVIE-RECOMMENDER-
cd HYBRID-MOVIE-RECOMMENDER-
pip install -r requirements.txt
```

---

## ▶️ Run Locally

```bash
# For terminal-based interaction
python main.py

# If using Streamlit
streamlit run main.py
```

---

## 📸 Sample Output

```
You searched for: "Interstellar"

Recommended Movies:
- Inception
- The Martian
- Gravity
- Arrival
```

---

## 🔗 Live Demo

🚧 *Not yet deployed. Coming soon on Streamlit Cloud!*

---

## 📂 Related Projects

- [Customer Segmentation](https://github.com/Iammanan07/Customer-segmentation-Using-K-means-Clustering)
- [Aviation Accident Analysis](https://github.com/Iammanan07/Aviaation-accident-Analysis-EDA-)
- [Customer Churn Predictor](https://github.com/Iammanan07/Customer-Churn-Prediction-)

---

## 👨‍💻 Author

**Abhishek Pandey**  
📧 [Email](mailto:Pandeymanan637@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-pandey-vobgb/)  
🐙 [GitHub](https://github.com/Iammanan07)

---

## 📃 License

This project is licensed under the MIT License.

---

<p align="center">
  <i>Crafted with ❤️ and a love for good movies.</i>
</p>
