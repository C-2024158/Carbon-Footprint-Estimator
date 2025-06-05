# 🌱 Carbon Footprint Estimator (Regression Model)

Estimate a person's **weekly CO₂ emissions (in kg)** based on their **lifestyle inputs** using simple regression models.

---

## 📊 Dataset Used

This project uses a **synthetic dataset** of 15 entries simulating real-world scenarios with the following features:

- **Diet Type**: ['Omnivore', 'Vegetarian', 'Vegan']
- **Transport Mode**: ['Car', 'Public Transit', 'Bicycle']
- **Weekly km**: Distance traveled per week (numeric)
- **Electricity kWh**: Weekly electricity consumption (numeric)
- **CO₂ kg/week**: Total weekly carbon footprint (target)

---

## 🧠 Approach Summary

1. **One-Hot Encoding** for categorical features (`Diet Type`, `Transport Mode`)
2. **Train-test split** for evaluation (70/30)
3. **Two Models**:
   - Linear Regression
   - Decision Tree Regressor
4. **Evaluation Metric**:
   - Mean Squared Error (MSE)
5. **Visualization**:
   - Line plot comparing actual vs predicted CO₂ emissions

---

## 📦 Dependencies

Install the following packages before running the notebook:

```bash
pip install pandas scikit-learn matplotlib
