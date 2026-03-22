# 🌍 Geocoder & Location Mapping App

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Geocoding-Location%20API-green">
  <img src="https://img.shields.io/badge/Folium-Map%20Visualization-orange">
  <img src="https://img.shields.io/badge/Status-Active-success">
</p>

---

## 📌 Overview

This project is a **Geocoder Application** built using Python that converts addresses into geographic coordinates (latitude and longitude) and visualizes them on an interactive map.

It demonstrates:
- API-based geocoding  
- Location data processing  
- Interactive map visualization  

---

## 🚀 Features

- 📍 Convert addresses into latitude & longitude  
- 🌐 Geocode using external APIs  
- 🗺️ Visualize locations on interactive maps  
- 📊 Process and store location data  
- ⚡ Handle multiple addresses efficiently  

---

## 🛠️ Tech Stack

| Category        | Technology Used        |
|----------------|----------------------|
| Language       | Python               |
| Geocoding API  | Geopy / Nominatim    |
| Visualization  | Folium               |
| Data Handling  | Pandas               |


---

## ⚙️ How It Works

1. Input addresses are provided (CSV / list)  
2. Geocoding API converts addresses → coordinates  
3. Coordinates are processed and stored  
4. Locations are plotted on an interactive map  
5. Map is exported as an HTML file  

---

## ▶️ Getting Started

### 🔧 Prerequisites

- Python 3.x installed  

---

### 📦 Install Dependencies

```bash
pip install pandas geopy folium
▶️ Run the Application
python app.py
📊 Output
Latitude & Longitude for each address
Interactive HTML map showing locations
