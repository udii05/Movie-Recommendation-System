# 🎬 CineFinds — Movie Recommendation System

> A minimal, Netflix-inspired movie recommender powered by cosine similarity and a smooth cinematic UI.

---

## 📛 Badges

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Django-4.x-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Machine%20Learning-Cosine%20Similarity-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/UI-Netflix%20Dark-black?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/udii05/Movie-Recommendation-System?style=for-the-badge">
</p>

---

## 🧠 Tech Stack

| Category | Technologies |
|---------|--------------|
| Backend | Django, Python |
| Data | Pandas, PyArrow, Parquet |
| Frontend | HTML, CSS, jQuery UI |
| ML Logic | Cosine Similarity |
| UI Theme | Netflix Style (Mint)|

---

## 🛠️ Getting Started

```bash
git clone https://github.com/udii05/Movie-Recommendation-System.git
cd Movie-Recommendation-System

python -m venv venv
venv\Scripts\activate   # or source venv/bin/activate (Mac/Linux)

pip install -r requirements.txt
python manage.py runserver
```
---

### **▶️ Run the Application**
Once setup is complete, start the development server:
```sh
python main.py
```
Then open your browser and go to:
```sh
http://127.0.0.1:8000/

```
### **🧠 Model Overview**
This system uses a similarity-based recommendation algorithm trained on real-world movie metadata.
Training or replacing the model can be done using the included Jupyter Notebook.
### **📂 Project Structure**
```tree
📁movie-recommendation-system/
│── views.py
│── urls.py
│── templates/
│   ├── index.html
│   └── result.html
│── static/recommender/
│   ├── cursor.css
│   ├── navbar.css
│   ├── page.css
│   └── fog animations
movie_recommendation/
static/
│── top_2k_movie_data.parquet
│── demo_model.parquet
manage.py
requirements.txt
```
### **⭐ Support**
If you liked this project, please star the repo — it really motivates me.
- and follow for more updates!
---

Udita Chakraborty
<p align="left"> <a href="https://github.com/udii05"> <img src="https://img.shields.io/badge/GitHub-udii05-black?style=flat-square&logo=github"> </a> <a href="https://www.linkedin.com/in/udita-chakraborty-b890982a2/"> <img src="https://img.shields.io/badge/LinkedIn-Udita%20Chakraborty-blue?style=flat-square&logo=linkedin"> </a> <a href="https://www.instagram.com/u_dii05"> <img src="https://img.shields.io/badge/Instagram-@u_dii05-e84393?style=flat-square&logo=instagram"> </a> </p>
