# 🏛️ Museum Collection Insights
![Dashboard Preview](Datasets/wp2186239-museum-wallpapers.jpg)

**A Data Analytics & Visualization Project Using SQL Server and Power BI**

This project offers a comprehensive analytical view of the **Museum of Modern Art's (MoMA)** collection data from **1929 to 2024**, combining advanced SQL queries with interactive Power BI dashboards to extract key insights about artists, acquisitions, mediums, and institutional trends.

---

## 📦 Dataset Overview

The project utilizes two main datasets:

- **Artworks.csv** — Details of each artwork: Title, Artist, Medium, Dimensions, Classification, Department, Date Acquired, etc.
- **Artists.csv** — Artist metadata including Name, Gender, Nationality, and Life Span

> **Source**: Public MoMA collection dataset

---

## 🛠 Tools & Technologies

- **SQL Server** – Data cleaning, transformation, and advanced analysis
- **Power BI** – Interactive dashboard design and insight visualization
- **DAX** – Custom measures and dynamic aggregation logic
- **Excel/CSV** – Initial dataset formatting and inspection

---

## 🔍 Data Processing & Cleaning Highlights

- Standardized textual columns (e.g., Gender, Nationality) using SQL string functions
- Extracted clean date values from complex textual year formats
- Decomposed multi-artist rows using `STRING_SPLIT()` for proper normalization
- Applied `ROW_NUMBER()` with CTEs to remove duplicate entries
- Converted dimensional fields to numerical values (Height/Width)
- Derived new fields such as `Acquired_Year`, `Period_Category`, and more

---

## 📊 Key Business Insights

### 🎨 How Modern is the Collection?
- **80%+** of artworks were acquired post-1966
- Largest contribution: **21st Century Collection (2006–2024)** with over **51,000 artworks**
- Demonstrates the museum's strong commitment to modern and contemporary art

### 🧑‍🎨 Most Featured Artists
- **Ludwig Mies van der Rohe** tops the list with **15,491 artworks**
- Other notable mentions: *Eugène Atget*, *Louise Bourgeois*, *Pablo Picasso*, *Henri Matisse*

### 🕒 Acquisition Trends
- Major acquisition spikes in:
  - **1966–1985** (Modern Growth)
  - **2006–2024** (21st Century Expansion)

### 🗂️ Artwork Classification
- Leading categories: *Photograph*, *Print*, *Illustrated Book*
- Indicates the museum's diverse yet print-heavy collection

### 🌍 Nationality Distribution
- Predominantly *American* artists, followed by *French*, *German*, and *British*
- Highlights MoMA’s strong North American and European influence

### 🏛️ Department & Artist Influence
Each department is anchored by key artists:
| Department                         | Top Artist                   | Total Artworks |
|------------------------------------|-------------------------------|----------------|
| Architecture & Design              | Ludwig Mies van der Rohe      | 15,474         |
| Photography                        | Eugène Atget                  | 5,031          |
| Drawings & Prints                  | Louise Bourgeois              | 3,325          |
| Painting & Sculpture               | Pablo Picasso                 | 72             |
| Fluxus Collection                  | George Maciunas               | 314            |

---

## 📊 Power BI Dashboard Overview

The dashboard is designed with a **2-page layout** for optimal navigation and interactivity:

### 🖼️ Page 1: Museum Overview
- Acquisition trends over time
- Classification and department breakdown
- Artist contributions and nationality map

### 👤 Page 2: Interactive Artist Profile
- Artist details (Name, Gender, Nationality, Lifespan)
- Total artwork count
- Gallery of artworks (Title, Medium, Year, etc.)

### 📷 Preview

![Dashboard Preview](Datasets/Museum_Collection_Insights_page-0001.jpg)

---

## 💡 Suggested Additional Analysis

| Analysis | Purpose |
|---------|---------|
| Gender Diversity Trends | Evaluate inclusion over decades |
| Lifespan vs Acquisition | Determine posthumous impact |
| Department-wise Growth | Identify areas of curatorial expansion |
| Medium Evolution | Understand material preferences over time |

---

## 📌 Project Author

**Shreya Pandey**  
*Data Analytics Placement Project | 2025*  
*SQL | Power BI | Data Modeling | Visualization*

🔗 [LinkedIn](https://www.linkedin.com/in/shreya-pandey-97252431b/)
📁 GitHub: [github.com/Shreya Pandey](https://github.com/shreya579/MoMA-ModernArt-Analytics)

---
