# 🌍 Global AQI Excel Dashboard

An interactive Microsoft Excel dashboard for exploring **global Air Quality Index (AQI)** observations across countries and dates.

The project turns a country-level AQI dataset into a compact analytical view of **overall AQI, status distribution, country-level variation, temporal patterns, and extreme pollution observations**.

> 📊 Dashboard: Microsoft Excel  
> 📁 Dataset: 21,964 AQI observations across 142 countries  
> 🗓️ Coverage: 21 July 2022 – 6 November 2025

---

## 📸 Dashboard Preview

![Global AQI Dashboard]
<img width="1584" height="845" alt="Screenshot 2026-09-23 134412" src="https://github.com/user-attachments/assets/26b69a52-d694-4554-80f3-ff4dbb136197" />

---

## 🔎 Key Insights

### Overall AQI profile

| Metric | Value |
|---|---:|
| Observations | **21,964** |
| Countries | **142** |
| Average AQI | **62.4** |
| Median AQI | **52** |
| Maximum observed AQI | **963** |

### ⚠️ Important: Maximum AQI vs. Highest Average AQI

These are two different measurements:

- **Highest recorded AQI:** **China — 963**, observed on **20 April 2023**.
- **Highest country average AQI:** **India — 219.8**.
- China’s average AQI is **173.3**, while India’s maximum observed AQI is **946**.

So, **China is the country with the highest single AQI observation**, whereas **India has the highest average AQI in this dataset**.

### AQI status distribution

| Status | Share of observations |
|---|---:|
| Good | **48.5%** |
| Moderate | **35.8%** |
| Unhealthy for Sensitive Groups | **10.2%** |
| Unhealthy | **4.2%** |
| Very Unhealthy | **0.9%** |
| Hazardous | **0.5%** |

Overall, **84.3%** of observations are classified as Good or Moderate, while **15.8%** are at least Unhealthy for Sensitive Groups.

### Country-level variation

| Country | Average AQI | Maximum AQI |
|---|---:|---:|
| India | **219.8** | 946 |
| China | **173.3** | **963** |
| Iraq | **155.1** | 590 |
| Iran | **152.9** | 308 |
| Qatar | **142.0** | 183 |
| Bangladesh | **140.3** | 532 |

At the lower end of the dataset, Guam has an average AQI of **3.1**, followed by the Cayman Islands (**10.4**) and Brunei (**11.7**).

### Temporal pattern

The highest monthly global-average AQI values in the workbook occur around late 2024 and early 2025:

- **February 2025:** 81.7
- **January 2025:** 80.9
- **December 2024:** 76.2

The yearly average AQI is:

| Year | Average AQI |
|---|---:|
| 2022 | 60.8 |
| 2023 | 65.8 |
| 2024 | 64.2 |
| 2025 | 62.1 |

These figures describe the observations present in this workbook; they do not establish causal reasons for changes in air quality.

---

## 🧭 What the Dashboard Explores

The dashboard is designed to answer questions such as:

- How does AQI vary across countries?
- What share of observations falls into each AQI category?
- Which countries have the highest **average** AQI?
- Where do the highest **single AQI observations** occur?
- How does the global average AQI change over time?
- Which periods show unusually high AQI levels?

---

## 🛠️ Tools & Techniques

**Tools**
- Microsoft Excel
- Pivot Tables / Pivot Charts
- Excel dashboarding
- Data filtering and interactive exploration

**Analytical techniques**
- Descriptive statistics
- Country-level aggregation
- Status/category distribution
- Time-series aggregation
- Extreme-value analysis

---

## 📂 Dataset Structure

The main observation table contains:

| Column | Description |
|---|---|
| `Date` | Observation date |
| `Country` | Country associated with the observation |
| `Status` | AQI category/status |
| `AQI Value` | Numeric AQI measurement |

The workbook also contains dashboard/pivot content used for visual exploration.

---

## ⚠️ Interpretation Notes

AQI values depend on the underlying AQI methodology, pollutant measurements, monitoring coverage, and aggregation method. Country-to-country comparisons should therefore be interpreted in the context of the dataset's source and measurement conventions.

This project is intended as a **data analysis and dashboarding exercise**, not as a public-health assessment or causal study.

---

## 🚀 Repository

**GitHub:** https://github.com/Er-Rajas/AQI-excel-dashboard

The repository contains the Excel workbook, dashboard documentation, and project README.

---

## 👤 Author

**Rajas Ajay Bhingarde**

Electrical Engineering • AI & Data Science

GitHub: https://github.com/Er-Rajas

---

⭐ If you find the project useful, feel free to star the repository.
