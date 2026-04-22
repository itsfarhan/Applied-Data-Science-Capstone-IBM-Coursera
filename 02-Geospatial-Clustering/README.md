# 🗺️ 02 — Geospatial Segmenting & Clustering
### Applied Data Science Capstone

[![Stage](https://img.shields.io/badge/Stage-Clustering-teal?style=flat-square)](../)
[![Algorithm](https://img.shields.io/badge/Algorithm-K--Means-9cf?style=flat-square)](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)

---

## 📌 Overview

This stage focuses on **geospatial segmentation** of New York City neighborhoods. By combining borough data with venue profiles, we use unsupervised learning to identify similar neighborhood clusters.

---

## 📓 Notebooks

| File | Description |
|------|-------------|
| [`02a-Data-Acquisition.ipynb`](02a-Data-Acquisition.ipynb) | Data acquisition and structured DataFrame construction |
| [`02b-Geocoding-and-Mapping.ipynb`](02b-Geocoding-and-Mapping.ipynb) | Geospatial encoding and mapping neighborhood coordinates |
| [`02c-Neighborhood-Segmentation.ipynb`](02c-Neighborhood-Segmentation.ipynb) | **K-Means Clustering** based on venue density and profiles |

---

## 🔬 Techniques Used

- **Web scraping** for structured neighborhood data
- **Geocoding** with Geopy and Nominatim
- **Foursquare API** integration for venue category extraction
- **K-Means Clustering** to segment neighborhoods into functional groups
- **Folium** for interactive spatial visualizations

---

## 🔗 Navigation

| | Link |
|--|------|
| ⬅️ Previous | [01 — Exploratory Analysis](../01-Exploratory-Analysis/) |
| ➡️ Next | [03 — Data & Methodology](../03-Data-and-Methodology/) |
| 🏠 Home | [Project Root](../) |
