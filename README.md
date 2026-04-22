<div align="center">

# 🗽 Applied Data Science Capstone
### IBM Data Science Professional Certificate · Coursera

[![IBM](https://img.shields.io/badge/IBM-Data%20Science-054ADA?style=for-the-badge&logo=ibm&logoColor=white)](https://www.coursera.org/professional-certificates/ibm-data-science)
[![Coursera](https://img.shields.io/badge/Coursera-Certified-0056D2?style=for-the-badge&logo=coursera&logoColor=white)](https://www.coursera.org)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Foursquare](https://img.shields.io/badge/Foursquare-API-F94877?style=for-the-badge&logo=foursquare&logoColor=white)](https://developer.foursquare.com/)

</div>

---

## 📌 Project Overview

> **"The Battle of Neighborhoods"** — A location intelligence study that identifies the **best New York City borough for opening an Indian restaurant**, powered by the Foursquare Places API, geospatial clustering, and data-driven storytelling.

This is the **capstone project** of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) on Coursera. The project simulates a real-world data science consultancy task: a client wants to open an Indian restaurant in New York City and needs evidence-based recommendations on *where* to set up shop.

---

## 🧠 Problem Statement

New York City is one of the most competitive restaurant markets in the world. For a new Indian restaurant to succeed, location is everything. This project answers:

- **Which NYC borough has the least Indian restaurant competition?**
- **Which neighborhoods have the highest potential for a new Indian eatery?**
- **What does the venue landscape look like across different areas?**

---

## 🔬 Methodology

```
Data Collection → Geospatial Analysis → Foursquare API → K-Means Clustering → Visualization → Recommendation
```

| Step | Description |
|------|-------------|
| 📥 **Data Collection** | NYC neighborhood data (boroughs, coordinates) + Foursquare venue data |
| 🗺️ **Geospatial Mapping** | Folium choropleth maps of neighborhoods & venue density |
| 🤖 **K-Means Clustering** | Grouped neighborhoods by venue category profiles |
| 📊 **Statistical Analysis** | Ranked boroughs by Indian restaurant density & competition index |
| 💡 **Recommendation** | Identified top neighborhoods with high foot traffic & low Indian eatery saturation |

---

## 🏗️ Repository Structure

```
📦 Applied-Data-Science-Capstone-IBM-Coursera
│
├── 📁 01-Exploratory-Analysis/
│   └── 01-Initial-Scoping.ipynb        # Project setup & initial exploration
│
├── 📁 02-Geospatial-Clustering/
│   ├── 02a-Data-Acquisition.ipynb      # Scraping & DataFrame construction
│   ├── 02b-Geocoding-and-Mapping.ipynb # Latitude/Longitude integration
│   └── 02c-Neighborhood-Segmentation.ipynb # K-Means clustering analysis
│
├── 📁 03-Data-and-Methodology/
│   ├── Introduction_Business Problem.pdf
│   └── Data_Section.pdf
│
└── 📁 04-Final-Presentation/
    ├── 04-Final-Recommendation-Engine.ipynb ⭐ Final Solution
    ├── indian_rest_stats_ny.csv
    ├── borough_rating.html
    ├── Ratings.jpg
    └── Report.pdf
```

---

## 🛠️ Tech Stack

<div align="center">

| Category | Tools |
|----------|-------|
| **Language** | Python 3 |
| **Analysis** | Jupyter Notebook, Pandas, NumPy |
| **Visualization** | Folium, Matplotlib, Seaborn |
| **Geospatial** | Geopy, Nominatim |
| **Machine Learning** | Scikit-learn (K-Means Clustering) |
| **API** | Foursquare Places API |

</div>

---

## 📊 Key Findings

- 🏆 **Staten Island** emerged as the most favorable borough — lowest Indian restaurant density relative to total venues.
- 🗺️ Interactive maps reveal clear clustering patterns across all 5 NYC boroughs.
- 📈 K-Means clustering successfully segmented ~300+ neighborhoods into distinct venue-profile groups.
- 🍛 Indian cuisine represents **< 1%** of total venues in most neighborhoods — highlighting a significant market gap.

---

## 📂 Quick Start

```bash
# Clone the repository
git clone https://github.com/itsfarhan/Applied-Data-Science-Capstone-IBM-Coursera.git
cd Applied-Data-Science-Capstone-IBM-Coursera

# Install dependencies
pip install pandas numpy matplotlib seaborn folium scikit-learn geopy requests

# Open the final recommendation engine
jupyter notebook "04-Final-Presentation/04-Final-Recommendation-Engine.ipynb"
```

---

## 📄 Reports & Deliverables

| Document | Description |
|----------|-------------|
| [📋 Business Problem](03-Data-and-Methodology/Introduction_Business%20Problem.pdf) | Problem framing & stakeholder context |
| [📊 Data Section](03-Data-and-Methodology/Data_Section.pdf) | Data sources, acquisition strategy & feature engineering |
| [📝 Final Report](04-Final-Presentation/Report.pdf) | Complete analysis writeup with conclusions |
| [🗺️ Interactive Map](04-Final-Presentation/borough_rating.html) | Folium choropleth — open in browser |

---

## 🎓 Certificate

This project is the **final capstone** of the **IBM Data Science Professional Certificate** — a 10-course specialization covering:
`Python` · `SQL` · `Data Analysis` · `Data Visualization` · `Machine Learning` · `Applied DS`

---

<div align="center">

Made with ❤️ and lots of ☕ · [Farhan Ahmed](https://farhanahmed.pro/home)

</div>
