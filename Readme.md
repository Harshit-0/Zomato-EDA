# 🍽️ Zomato Bangalore Restaurants - Data Analysis Project

This project focuses on exploring restaurant trends, ratings, and customer preferences in Bangalore using Zomato’s dataset. It involves data cleaning, preprocessing, and various visualizations to uncover hidden insights.

---

## 📁 Dataset Source

The original dataset is available here:  
🔗 [Zomato Bangalore Restaurants Dataset on Kaggle](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)

---

## ⚠️ Note on Dataset Size

The full dataset is over **547 MB**, which exceeds GitHub’s 100 MB limit.  
➡️ Therefore, this repository uses a **sample of 5,000 rows** (`zomato_sampled.csv`) for demonstration purposes.

To use the full dataset:  
1. Download it from Kaggle using the link above.  
2. Replace the sample CSV with the full one.  
3. Change the `read_csv()` line in the code to:

```python
df = pd.read_csv("zomato.csv", encoding="latin1")```





## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook  
- **Platform:** GitHub, Kaggle  
- **Dataset Source:** [Kaggle - Zomato Bangalore Restaurants](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)




## 🌟 Project Highlights

- ✅ Cleaned and preprocessed critical columns like `rate` and `approx_cost(for two people)`
- ✅ Converted strings like `"3.5"` and `"NEW"` to numerical values for analysis
- ✅ Handled missing and inconsistent data gracefully
- ✅ Filtered and analyzed restaurant popularity by votes and ratings
- ✅ Created multiple data visualizations:
  - Top 10 restaurants by vote count (Bar Plot)
  - Rating distribution by cuisine type (Violin Plot)
  - Average cost vs rating trends (Line Plot)
  - Top 10 restaurants in Bangalore only (Bar Plot)
- ✅ Used Seaborn and Matplotlib for clean visual design
- ✅ Organized with markdown cells for readability in Jupyter Notebook

 
