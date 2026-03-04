# 🏴‍☠️ Money Heist EDA Project

This project performs **Exploratory Data Analysis (EDA)** on the popular TV series *Money Heist*.  
The objective is to analyze episode ratings, watch time, seasons, and yearly trends using Python.

---

## 📌 Dataset Information

The dataset contains the following columns:

- Season  
- Episode  
- Name  
- On Air  
- Year  
- IMDB  
- Watch Time (minutes)  
- Summary  

---

## 🎯 Project Objectives

- Analyze IMDB rating distribution  
- Identify highest rated episodes  
- Find number of episodes in each season  
- Determine which year had the most episodes  
- Calculate total watch time per season  
- Study rating trends over the years  
- Analyze correlation between Watch Time, Year, and IMDB  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Analysis Performed

✔ Data inspection using `shape`, `columns`, `info()`, `describe()`  
✔ Histogram of IMDB ratings  
✔ Boxplot of IMDB ratings  
✔ Filtering episodes with high ratings  
✔ Seasons extracted using `unique()`  
✔ Episodes per season using `groupby()`  
✔ Barplot for season with highest episodes  
✔ Countplot for year-wise episode count  
✔ Barplot for episodes with highest runtime  
✔ Barplot for highest IMDB rated episodes  
✔ Boxplot of IMDB over years  
✔ Total watch time per year  
✔ Correlation heatmap  
✔ Pointplot of average IMDB rating over years  
✔ Season with longest total watch time  

---

## 📈 Key Insights

- Some episodes have IMDB ratings above 8.5  
- Certain seasons contain more episodes  
- Ratings vary slightly across different years  
- Watch Time and IMDB ratings show moderate correlation  
- One season has the highest overall watch duration  

---

## ▶ How to Run This Project

1. Clone this repository:
   ```
   git clone https://github.com/harithaharikumar100-gif/money-heist.eda.git
   ```
2. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Run the `MoneyHeist_EDA.ipynb` file.

---

## 📂 Project Structure

```
money-heist-eda/
│
├── money_heist.xls
├── MoneyHeist_EDA.ipynb
└── README.md
```

---

## 🚀 Author

Haritha P  
Aspiring Data Scientist | AI Enthusiast  

---

⭐ If you found this project useful, feel free to star the repository!
