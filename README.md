# Zomato-Data-Analysis
it helps to analyse restaurant data of zomato
# 🍽️ Zomato Data Analysis Project

A data analysis project that explores restaurant data from Zomato to uncover insights about dining trends, customer preferences, ratings, and ordering behaviour.

---

## 📁 Project Structure

```
├── Zomato_data__.csv                        # Dataset
├── Zomato_Data_Analysis_Project.ipynb       # Jupyter / Colab Notebook
├── requirements.txt                         # Python dependencies
└── README.md                                # Project documentation
```

---

## 📊 Dataset

The dataset contains **148 restaurant records** with the following columns:

| Column | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating (out of 5) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (₹) |
| `listed_in(type)` | Type of restaurant (Buffet, Cafes, Dining, Other) |

---

## 🔍 Analysis Performed

### 1. Type of Restaurants
- Plotted a count of restaurants by category using a bar chart.
- **Conclusion:** The majority of restaurants fall in the **Dining** category.

### 2. Votes by Restaurant Type
- Grouped total votes by restaurant type and plotted a line chart.
- **Conclusion:** **Dining** restaurants received the maximum number of votes.

### 3. Rating Distribution
- Plotted a histogram of restaurant ratings.
- **Conclusion:** Most restaurants received ratings between **3.5 and 4.0**.

### 4. Average Spending by Couples
- Analysed the approximate cost for two people using a count plot.
- **Conclusion:** The majority of couples prefer restaurants with an approximate cost of **₹300**.

### 5. Online vs Offline Order Ratings
- Compared ratings for online and offline orders using a box plot.
- **Conclusion:** **Online orders** received higher ratings compared to offline orders.

### 6. Online Order Availability by Restaurant Type (Heatmap)
- Created a pivot table and heatmap showing the count of restaurants by type and online order availability.
- **Conclusion:** Dining restaurants dominate, with **77** accepting online orders and **33** not accepting them.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data loading and manipulation
- **NumPy** — numerical operations
- **Matplotlib** — plotting charts
- **Seaborn** — statistical visualisations

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open `Zomato_Data_Analysis_Project.ipynb` in Jupyter Notebook or upload it to [Google Colab](https://colab.research.google.com/).

Make sure `Zomato_data__.csv` is in the same directory, or update the file path inside the notebook accordingly.

---

## 📌 Key Insights Summary

| Question | Finding |
|---|---|
| Most common restaurant type | Dining |
| Highest voted category | Dining |
| Most common rating range | 3.5 – 4.0 |
| Most preferred cost for two | ₹300 |
| Higher rated order mode | Online orders |

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
