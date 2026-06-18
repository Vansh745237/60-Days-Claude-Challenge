# 🚗 Fuel Analytics Dashboard

A responsive and interactive Fuel Analytics Dashboard built using **HTML, CSS, JavaScript, and SVG**. The dashboard analyzes different fuel types (Petrol, Diesel, CNG, EV, and E85) based on running cost, emissions, maintenance expenses, refueling time, and vehicle age.

## 📌 Overview

This project provides a visual comparison of various fuel options and helps users understand:

- Cost per kilometer
- CO₂ emissions per kilometer
- Maintenance cost per kilometer
- Refuel/Recharge time
- Vehicle age impact on running cost
- E85 fuel feasibility and break-even analysis

The dashboard is designed with a modern **glassmorphism UI**, dark theme, and fully responsive layout.

---

## ✨ Features

### 📊 KPI Cards

Displays key metrics such as:

- Your fuel cost per km
- E85 cost per km
- E85 premium/penalty compared to Petrol
- E85 break-even fuel price
- Estimated monthly fuel expense

### 📈 SVG Charts

#### Cost per Kilometer (Bar Chart)

Compare running costs across:

- Petrol
- Diesel
- CNG
- EV
- E85

#### CO₂ Emissions (Doughnut Chart)

Visual representation of emissions generated per kilometer.

#### Cost vs Vehicle Age (Line Chart)

Shows how running costs vary as vehicle age increases.

#### Animated E85 Score Gauge

Displays an overall E85 suitability score out of 10.

---

## 🚘 Vehicle Configuration

| Parameter | Value |
|------------|--------|
| Vehicle | JUPITER ZX |
| Fuel Type | Petrol |
| Vehicle Age | 4 Years |
| Usage | Mixed |
| Distance | 500 km/month |

---

## 🧮 Calculations Performed

### Average Cost per km

```text
Cost/km = Fuel Cost (INR) ÷ Distance (km)
```

### Average CO₂ per km

```text
CO₂/km = CO₂ Emitted (kg) ÷ Distance (km)
```

### Average Maintenance per km

```text
Maintenance/km = Maintenance Cost (INR) ÷ Distance (km)
```

### E85 Pump Saving

```text
((Petrol Price − E85 Price) ÷ Petrol Price) × 100
```

### E85 Running Penalty

```text
((E85 Cost/km − Petrol Cost/km) ÷ Petrol Cost/km) × 100
```

### E85 Break-even Price

```text
(E85 Mileage ÷ Petrol Mileage) × Petrol Price
```

---

## 🚦 Vehicle Age Buckets

Vehicles are categorized into:

| Bucket | Age |
|----------|----------|
| New | 0–2 Years |
| Mid-Life | 3–5 Years |
| Aged | 6–9 Years |
| Old | 10+ Years |

The dashboard highlights the current vehicle age category and compares:

- Cost/km
- Maintenance/km

across age groups.

---

## 🌱 E85 Evaluation Score

The E85 score is calculated out of 10 using:

| Metric | Weight |
|----------|----------|
| Cost Efficiency | 4 Points |
| CO₂ Reduction | 3 Points |
| Refuel Time | 2 Points |
| Maintenance | 1 Point |

---

## 🎨 UI Design

### Theme

- Background: `#0a0f1e`
- Glassmorphism Cards
- Smooth Animations
- Responsive Layout

### Fuel Colors

| Fuel | Color |
|--------|--------|
| Petrol | Blue |
| Diesel | Grey |
| CNG | Green |
| EV | Purple |
| E85 | Amber |

---

## 📱 Responsive Design

Optimized for:

- Mobile Devices (375px+)
- Tablets
- Laptops
- Desktop Screens (1440px+)

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- SVG Graphics

No external libraries, frameworks, or CDNs were used.

---

## 📂 Project Structure

```text
Day-17/
│
├── day17.html
├── README.md
├── screenshot-1.png
├── screenshot-2.png
└── screenshot-3.png
```

---

## 🚀 Getting Started

Open the project folder and launch:

```text
dashboard.html
```

in any modern web browser.

No installation, dependencies, frameworks, or setup steps are required.

---

## 📸 Screenshots

The project includes screenshots demonstrating:

- Dashboard Overview
- Fuel Cost Comparison
- E85 Analysis and Score

---

## 📈 Key Insights

- Compare running costs across fuel types.
- Understand long-term vehicle ownership costs.
- Evaluate environmental impact through CO₂ analysis.
- Determine whether E85 is economically viable.
- Identify the best fuel option based on usage patterns.

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Analysis and Metric Calculation
- SVG-Based Data Visualization
- Responsive Web Design
- Glassmorphism UI Design
- Interactive Dashboard Development
- JavaScript DOM Manipulation

---

## 👨‍💻 Author

**Vansh Bathla**

- GitHub: https://github.com/Vansh745237
- B.Tech CSE (Data Science)
- ABES Engineering College

---

⭐ If you found this project useful, consider giving it a star.
