---

# 🛍️ Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project performs **customer segmentation** on a mall customer dataset using the **K-Means clustering algorithm**. The dataset includes demographic and behavioral information such as age, gender, annual income, and spending score.

The primary objective is to group customers based on similar purchasing patterns and characteristics, enabling mall management to make **data-driven marketing and business decisions**.

---

## 🎯 Project Objectives

* Segment customers using unsupervised machine learning
* Identify high-value (premium) customers
* Analyze average and low-spending customer groups
* Support targeted marketing and profitability optimization

---

## 📊 Business Insights

* **High Spending Score Customers**
  Focus on retention through loyalty programs, personalized offers, and premium services.

* **Average Spending Score Customers**
  Target with promotions and strategic campaigns to maximize revenue.

* **Low Spending Score Customers**
  Develop innovative engagement strategies to improve purchasing behavior.

---

## 📁 Dataset Information

**File Name:** `mall-customers-data.csv`
**Records:** 200
**Features:** 5

### Dataset Columns

| Column Name      | Description                                    |
| ---------------- | ---------------------------------------------- |
| `customer_id`    | Unique customer identifier                     |
| `gender`         | Gender of the customer (Male / Female)         |
| `age`            | Age of the customer                            |
| `annual_income`  | Annual income (in thousands of dollars)        |
| `spending_score` | Mall-assigned score based on spending behavior |

---

## 🧠 Methodology

1. **Exploratory Data Analysis (EDA)**

   * Data distribution analysis
   * Gender and income analysis
   * Spending behavior visualization

2. **Data Preprocessing**

   * Feature selection
   * Data scaling (if required)

3. **Clustering**

   * Applied K-Means clustering
   * Optimal number of clusters identified using the Elbow Method

4. **Visualization & Interpretation**

   * Cluster visualization
   * Behavioral insights from each cluster

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📈 Results

The K-Means model successfully segmented customers into distinct clusters, each representing unique demographic and spending patterns. These insights can be leveraged to improve marketing efficiency and customer engagement.

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/customer-segmentation-kmeans.git

# Navigate to the project folder
cd customer-segmentation-kmeans

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
```

---

## 📌 Conclusion

This project highlights the effectiveness of **unsupervised learning** in understanding customer behavior. By applying K-Means clustering, businesses can gain actionable insights to optimize customer engagement, marketing strategies, and profitability.

---

## 👤 Author

**Ashwin Vincent Koonissery**

GitHub: [https://github.com/ashwin8332](https://github.com/ashwin8332)

---

## 📜 License

This project is intended for **educational and research purposes**. Please follow the dataset’s original license terms when using it for commercial applications.

---

⭐ If you find this project useful, feel free to star the repository!
