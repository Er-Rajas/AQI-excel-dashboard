# 🌍 Global AQI Excel Dashboard

An interactive Excel dashboard for exploring **global Air Quality Index (AQI)** observations across countries and dates.

The project focuses on turning a country-level AQI dataset into a compact analytical view of **overall air quality, country-level variation, status distribution, temporal patterns, and extreme pollution events**.

> 📊 Dashboard: Built in Microsoft Excel  
> 📁 Dataset: 21,964 AQI observations across 142 countries  
> 🗓️ Coverage: 21 July 2022 – 6 November 2025

---

## 📸 Dashboard Preview

Upload your final dashboard screenshot to the repository and update the filename below.

![Global AQI Dashboard](dashboard.png)

---

## 🔎 Key Insights

### Overall AQI profile

| Metric | Value |
|---|---:|
| Observations | **21,964** |
| Countries | **142** |
| Average AQI | **62.4** |
| Median AQI | **52** |
| Maximum AQI | **963** |

### AQI status distribution

- **Good:** 48.5%
- **Moderate:** 35.8%
- **Unhealthy for Sensitive Groups:** 10.2%
- **Unhealthy:** 4.2%
- **Very Unhealthy:** 0.9%
- **Hazardous:** 0.5%

Overall, **84.3%** of observations are classified as either Good or Moderate, while **15.8%** are at least Unhealthy for Sensitive Groups.

### Country-level variation

The dataset shows substantial geographic variation in average AQI.

| Country | Average AQI | Maximum AQI |
|---|---:|---:|
| India | **219.8** | 946 |
| China | **173.3** | 963 |
| Iraq | **155.1** | 590 |
| Iran | **152.9** | 308 |
| Qatar | **142.0** | 183 |
| Bangladesh | **140.3** | 532 |

At the lower end of the dataset, Guam has an average AQI of **3.1**, followed by the Cayman Islands (**10.4**) and Brunei (**11.7**).

### Temporal pattern

The highest monthly global averages in the dataset occur around the winter period spanning late 2024 and early 2025:

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

These figures describe the observations present in this workbook; they should not be interpreted as a causal analysis of why air quality changed.

---

## 🧭 What the Dashboard Explores

The Excel dashboard is designed to answer questions such as:

- How does AQI vary across countries?
- What share of observations falls into each AQI category?
- Which countries record the highest average AQI?
- Where do extreme AQI values occur?
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

AQI values depend on the underlying AQI methodology, pollutant measurements, monitoring coverage, and aggregation method. Country-to-country comparisons therefore need to be interpreted in the context of the dataset's source and measurement conventions.

This project is intended as a **data analysis and dashboarding exercise**, not as a public-health assessment or causal study.

---

## 🚀 Repository

GitHub repository:

**https://github.com/Er-Rajas/AQI-excel-dashboard**

---

## 👤 Author

**Rajas Ajay Bhingarde**

Electrical Engineering • AI & Data Science

GitHub: **https://github.com/Er-Rajas**

---

⭐ If this project is useful, feel free to star the repository and explore the dashboard.
