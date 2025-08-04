# Global_Youtube_Status_EDA

# 📊 Global YouTube Statistics – Exploratory Data Analysis

This project presents an in-depth Exploratory Data Analysis (EDA) of a dataset titled **"Global YouTube Statistics"**. The goal is to uncover trends, insights, and patterns from YouTube channels across different categories, countries, and metrics such as subscriber count, video views, and channel types.

---

## 📁 Dataset Overview

The dataset contains global statistics of various YouTube channels. It includes information such as:

- Channel name
- Category
- Channel type
- Number of subscribers
- Number of video views
- Country

> 📌 **Source**: Assumed to be a structured CSV file with encoding handled using `latin1`.

---

## 🛠️ Tools & Libraries Used

- **Python** (Pandas, NumPy)
- **Matplotlib** and **Seaborn** for data visualization
- Jupyter Notebook for analysis and presentation

---

## 🧹 Data Preprocessing

- Loaded data using `pandas.read_csv()`
- Checked data types and null values with `.info()` and `.describe()`
- Verified duplicate records using `.duplicated().sum()`
- Formatted float values for cleaner display using `pd.set_option`

---

## 📈 Key Visualizations & Insights

### 1. 📊 Mean Subscribers by Category
- Grouped by `category` and calculated average subscribers.
- Visualized using a **bar chart**.
- Insight: Some categories have significantly higher average subscribers, hinting at more popularity.

### 2. 🥧 Channel Type Distribution
- Used `value_counts()` to compute channel type frequencies.
- Plotted as a **pie chart** showing proportionate distribution.

### 3. 📉 Scatter Plot: Subscribers vs. Video Views
- Visualized the relationship between subscribers and video views.
- Insight: A positive correlation is evident—channels with more subscribers generally have more video views.

### 4. 🌍 Top Countries by Total Subscribers
- Aggregated subscriber counts grouped by `Country`.
- Top 10 countries plotted using a **bar chart**.
- Insight: Countries like the US and India dominate the platform in total subscriber count.

---

## 🧠 Summary of Findings

- **Content categories** vary significantly in terms of average subscriber base.
- **Entertainment and music-related channels** tend to perform well globally.
- **Geographic trends** show higher subscriber counts in a few dominant regions.
- **Channel type distribution** highlights the platform’s diversity—individual creators, brands, music labels, etc.

---

## 🧭 Future Work

- Deep dive into **engagement metrics** if available (likes, comments, etc.)
- Time-series analysis for subscriber growth (if data available)
- Build a **recommendation model** for new content creators
- Perform **sentiment analysis** on video titles or descriptions

---

## 💾 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-eda.git
   cd youtube-eda


2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn numpy
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook EDA_Project.ipynb
   ```

---

## 📌 Project Structure

```bash
📁 youtube-eda/
│
├── EDA_Project.ipynb      # Main analysis notebook
├── README.md              # Project documentation
└── dataset.csv            # (Ensure this is in the correct path or update notebook)
```

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks to the dataset provider and the open-source Python community.

---

## 🔗 Connect with Me

Feel free to reach out if you have questions or suggestions.

📧 [yourname@example.com](mailto:yourname@example.com)
🌐 [yourportfolio.com](https://yourportfolio.com)
🐦 [Twitter](https://twitter.com/yourhandle) | 💼 [LinkedIn](https://linkedin.com/in/yourprofile)

---

```

---

Would you like me to also:
- Generate a `requirements.txt` file?
- Add badges (like Python version, license, etc.)?
- Help you upload it to GitHub?

Let me know what you need next!
```
