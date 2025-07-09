
# 🚗 Dynamic Pricing for Urban Parking Lots

Capstone Project | **Summer Analytics 2025**  
Hosted by: Consulting & Analytics Club × Pathway

---

## 📌 Problem Statement

Urban parking spaces are a limited and highly demanded resource. Fixed pricing leads to overuse or underutilization. This project develops a **real-time, data-driven dynamic pricing engine** for 14 urban parking lots using:

- Occupancy & Queue Data
- Traffic Conditions
- Vehicle Type
- Special Day Indicators
- Location-based Competition

---

## 🧠 Project Objectives

1. **Model 1**: Baseline Linear Price Update  
2. **Model 2**: Demand-Based Pricing Function  
3. **Model 3**: Competitive Pricing using Lat-Long and Nearby Prices  
4. **Streaming Inference**: Real-time simulation using **Pathway**
5. **Visualization**: Interactive line plots using **Bokeh**

---

## 🛠 Tech Stack

| Component        | Tool/Library     |
|------------------|------------------|
| Data Handling    | Python, Pandas, NumPy |
| Real-Time Stream | Pathway          |
| Visualization    | Bokeh            |
| Environment      | Google Colab     |

---

## 📊 Architecture Diagram (Mermaid)

```mermaid
graph TD
    A[CSV Dataset] --> B[Real-Time Stream (Pathway)]
    B --> C[Preprocessing]
    C --> D1[Model 1: Baseline]
    C --> D2[Model 2: Demand]
    C --> D3[Model 3: Competitive]
    D1 --> E[Emit Price]
    D2 --> E
    D3 --> E
    E --> F[Visualization in Bokeh]
```

---

## 🔁 Workflow

1. Ingest real-time parking data (CSV simulated stream)
2. Preprocess: normalize, encode vehicle types, traffic levels
3. Apply three layered pricing models
4. Output updated price in real time
5. Visualize pricing behavior for analysis

---

## 📌 How to Run

1. Open `dynamic_pricing_final_notebook.ipynb` in Google Colab  
2. Upload `dataset.csv`  
3. Run all cells  
4. View `dynamic_pricing_bokeh_plot.html` for visualization

---

## ✍️ Author

Developed as part of **Summer Analytics 2025** Capstone by Aniket Arjun Redekar 
Mentored by **Consulting & Analytics Club** × **Pathway**

---

