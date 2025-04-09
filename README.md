# FUTURE_DS_02
Customer Support Data Analysis &amp; Ticket Resolution
This project analyzes customer support tickets to identify common issues, evaluate response/resolution performance, and derive insights to improve customer service processes.

---

## 📊 Objective

- Clean and analyze customer support data
- Identify most frequent ticket types and subjects
- Calculate average resolution times
- Visualize customer satisfaction across channels
- Generate a word cloud from ticket descriptions

---

## 🛠 Tools & Libraries Used

- **Python**
  - pandas
  - matplotlib
  - seaborn
  - wordcloud
  - re (regex for cleaning)
- **Jupyter Notebook or any Python environment**

---

## 📁 Dataset

**File:** `customer_support_tickets.csv`  
Contains fields like:
- Ticket Type
- Ticket Subject
- Ticket Channel
- Ticket Description
- Customer Satisfaction Rating
- First Response Time
- Time to Resolution

---

## 📈 Visualizations Generated

- Bar chart of ticket type frequencies
- Horizontal bar chart of top 10 ticket subjects
- Bar chart of average resolution time by ticket type
- Bar chart of average customer satisfaction rating by channel
- Word cloud of cleaned ticket descriptions

---

## 🧹 Key Processing Steps

1. **Text Cleaning:** Removed punctuation, special characters, and converted text to lowercase.
2. **Time Conversion:** Parsed resolution and response timestamps.
3. **Resolution Calculation:** Measured resolution duration in hours.
4. **Grouping & Aggregation:** Used `groupby()` to summarize performance metrics.
5. **Visualization:** Created plots and a word cloud to highlight insights.

---

## 📦 Output

You’ll get:
- Multiple insight-driven plots
- A word cloud from ticket descriptions
- Average resolution and satisfaction scores by category

---

## 🧾 How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn wordcloud

