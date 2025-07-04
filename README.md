
# 🚗 Dynamic Pricing for Urban Parking Lots

This project is part of the **Certified Capstone Project - Summer Analytics 2025** by **Consulting & Analytics Club, IIT Guwahati** in collaboration with **Pathway**.

## 🧠 Objective
To develop a real-time dynamic pricing model for urban parking lots using:
- Real-time occupancy data
- Queue lengths
- Capacity
- Vehicle types
- And more...

## ✅ This Repository Contains
- `Model_1_Parking_Dynamic_Pricing.ipynb`: Google Colab notebook implementing Model 1 (Baseline Linear Pricing based on occupancy)
- `report.pdf`: A short explanation of the model, logic, and assumptions *(if uploaded)*

## 💡 Model 1 - Baseline Pricing
The pricing updates as:
```
Price(t+1) = Price(t) + α * (Occupancy / Capacity)
```
With:
- Base Price: $10
- Alpha: 2.5
- Price bounded between $5 and $30

## 📈 Tools Used
- Python
- Pandas, Numpy
- Bokeh (for visualization)
- Google Colab

## 📝 Report
Includes:
- Model logic
- Sample outputs
- Assumptions

## 🔗 Submission for Certification
This repository serves as the official submission for the capstone project.

---

> Made with ❤️ for Summer Analytics 2025
