# 📊 Web Traffic Analysis Report

This report presents an in-depth analysis of web traffic data based on hourly user sessions, engagement metrics, and traffic source performance.

## 🗂️ Dataset Overview

* **Source**: Google Analytics Export (`data-export.csv`)
* **Period**: Hourly data points across multiple days
* **Tools Used**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

## 🔧 Preprocessing Steps

* First row extracted as actual column headers
* Converted `DateHour` to datetime format
* Converted all numeric fields to proper types
* Extracted `Hour` column from datetime
* Handled missing values appropriately

---

## 📈 Key Metrics Summary

| Metric                              | Description                      |
| ----------------------------------- | -------------------------------- |
| 👥 **Users**                        | Total number of unique users     |
| 🔁 **Sessions**                     | Number of browsing sessions      |
| ⚡ **Engaged Sessions**              | Sessions with user interaction   |
| ⏱️ **Avg. Engagement Time/Session** | Time spent per session (seconds) |
| 📊 **Engagement Rate**              | % of sessions with engagement    |
| 📌 **Events per Session**           | Avg. number of tracked events    |

---

## 🌐 Top Traffic Sources

Analyzed by total sessions and user engagement:

* **Direct**
* **Organic Social**
* **Organic Search**
* **Referral**
* **Unassigned**

---

## ⏰ Hourly Traffic Trend

Most traffic was observed between **12 PM and 4 PM**, with lower activity during early morning hours. Useful for content scheduling or ad targeting.

---

## 📊 Engagement Analysis

* **Direct** and **Organic Social** showed the highest engagement.
* **Referral** and **Unassigned** channels need optimization.
* Event tracking is functional and useful for behavior insights.

---

## ✅ Recommendations

* Enhance content strategies for peak hours.
* Invest more in top-performing sources like SEO and social media.
* Improve underperforming channels (Referral, Unassigned).
* Continue expanding event tracking for deeper insights.

---

## 🛠️ Tech Stack

```bash
📦 Python Libraries:
- pandas
- numpy
- seaborn
- matplotlib
```

---

## 📌 Author

**Abhay Dubey** – [GitHub Profile](https://github.com/abhaydubey200)
🎯 Data Analytics • Web Development • Java • MERN Stack

