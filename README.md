# 🎬 Movie Recommendation System

This project is a simple **content-based movie recommendation system** made using Python.  
It takes a movie name as input and shows you 5 similar movies based on plot keywords.

---

## 📁 Dataset Used

I used the **Movie Metadata** dataset from Kaggle:  
https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv

I uploaded the dataset to GitHub for easy access in the notebook:  
[Click here for the CSV file](https://github.com/siddquy2004/Movie_Recommendation_System_AICTE/blob/main/movie_metadata.csv)

---

## 💡 How It Works

1. The system reads the `plot_keywords` from the dataset.
2. It uses **TF-IDF Vectorizer** to convert text data into numbers.
3. Then it calculates **cosine similarity** between movies.
4. Based on the input movie title, it finds and returns the **top 5 similar movies**.

---

## 🧪 Example

If you type:  
`The Godfather`

You may get results like:  
- The Godfather: Part II  
- Goodfellas  
- Scarface  
- Casino  
- Donnie Brasco

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas  
- Scikit-learn (for TF-IDF and cosine similarity)

---

## 📌 How to Run

1. Clone or download this repository.
2. Open the notebook in Jupyter or VS Code.
3. Run all the cells one by one.
4. At the end, enter any movie title and it will show 5 recommendations.

---

## 📈 Future Improvements

- Add user-based or hybrid recommendation.
- Make a web interface using Flask.
- Improve movie search with fuzzy matching.
- Add genres and actor/crew filters.

---

## 📎 License

This project is for learning and internship purposes only.
