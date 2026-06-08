# 🌍 Day 8 – Personal Environmental Health Analyzer

## 📌 Overview
On Day 8 of the **60 Days of AI Challenge**, I explored how AI can be used for environmental data analysis and dashboard creation.

Using Claude, I generated a **Personal Environmental Health Analyzer** that analyzes environmental factors such as Air Quality Index (AQI), PM2.5, PM10 levels, water quality metrics, health risks, and environmental health scores through an interactive dashboard.

---

## 🎯 Objective
Build an interactive environmental health dashboard that:

- Analyzes air and water quality data
- Calculates environmental health scores
- Visualizes AQI and pollution metrics
- Provides health risk assessments
- Generates personalized environmental recommendations
- Offers an interactive and responsive user experience

---

## 🛠️ Prompt Used

```text
Act as a Senior Data Analyst, Environmental Researcher, UX Designer, and Frontend Dashboard Developer.

Create a Claude Artifact called:
🌍 Personal Environmental Health Analyzer

DATA RULES

If a dataset is provided, use it. If no dataset is provided, automatically search the web for the latest AQI and water-quality data for the user's current city/location. If location is unavailable, ask for the city name first. Use the most recent available data, cite sources, clean the data, handle missing values, and validate quality before analysis.

ANALYSIS

Generate: cleanest city, most polluted city, highest AQI city, lowest AQI city, average AQI, number of cities analyzed, trends, anomalies, most surprising observation, executive summary.

INTERACTIVE DASHBOARD

Create a fully interactive Claude Artifact with:

📊 Key Metrics: average AQI, highest AQI city, lowest AQI city, number of cities analyzed, environmental health score.

📈 Visualizations: AQI comparison chart, PM2.5 comparison chart, PM10 comparison chart, city ranking chart, AQI distribution chart.

🎛 Interactive Filters: city selector, AQI range filter, pollutant selector, health-risk filter, date filter (if available), city comparison mode.

📋 City Detail Cards: AQI, PM2.5, PM10, air-quality category, health score, water-quality score.

🚦 AQI Categories: Good (Green), Satisfactory (Light Green), Moderate (Yellow), Poor (Orange), Very Poor (Red), Severe (Dark Red).

ENVIRONMENTAL HEALTH ANALYSIS

For the selected city explain AQI impact on lungs, sleep, energy levels, exercise performance, long-term health, and water-quality impact on hair fall, hair dryness, scalp health, skin dryness, acne, and sensitive skin.

Use risk indicators: 🟢 Low, 🟡 Moderate, 🔴 High.

PERSONAL REPORT CARD

Generate an Environmental Health Score (0–100) with breakdowns for Air Quality Score, Water Quality Score, and Overall Environmental Score.

Assign grades for Air Quality (A–F), Water Quality (A–F), Hair Risk, and Skin Risk.

INSIGHTS PANEL

Include: top 3 cleanest cities, top 3 most polluted cities, biggest anomaly, most surprising observation, recommended actions.

PERSONALIZED RECOMMENDATIONS

Provide: daily actions, indoor air improvements, outdoor activity guidance, hair-care recommendations, skin-care recommendations, water-quality improvement suggestions.

DESIGN

Modern, professional, mobile responsive, dark theme, smooth animations, premium UI, clean typography, dashboard-style layout, highly visual, colourful, LinkedIn-shareable.

OUTPUT

Generate a complete downloadable HTML application that is fully responsive and ready to save as index.html.

IMPORTANT

Do not provide code snippets. Create a complete interactive Claude Artifact with working charts, filters, cards, insights, report cards, and dashboards that users can interact with directly.
```

---

## 📂 Project Files

```
Day8/
│
├── index.html
├── day8.md
├── dashboard-screenshot-1.png
├── dashboard-screenshot-2.png
└── dashboard-screenshot-3.png
```

---

## 📸 Screenshots

Add your dashboard screenshots here.

### Dashboard Overview
<img width="954" height="436" alt="Screenshot 2026-06-08 133605" src="https://github.com/user-attachments/assets/1242a69a-9964-427c-aabb-ef69fdb10049" />


### Interactive Charts & Filters
<img width="948" height="443" alt="Screenshot 2026-06-08 133641" src="https://github.com/user-attachments/assets/bfd989da-4c8a-4f5b-a8fe-63178476a7d8" />


### Environmental Report Card
<img width="953" height="440" alt="Screenshot 2026-06-08 134158" src="https://github.com/user-attachments/assets/cb85f360-d739-44ad-82ef-8d4e49c46b45" />


---

## 🔍 Key Learnings

### 1. AI-Powered Dashboard Creation
Learned how AI can generate complete interactive dashboards with minimal manual coding.

### 2. Environmental Data Analysis
Understood how AQI, PM2.5, PM10, and water quality metrics can be analyzed and visualized.

### 3. Data Storytelling
Discovered how dashboards transform raw environmental data into actionable insights.

### 4. User Experience Design
Observed how filters, charts, scorecards, and recommendations improve dashboard usability.

### 5. Health Impact Interpretation
Learned how environmental conditions can affect:
- Respiratory health
- Sleep quality
- Physical performance
- Skin health
- Hair health

### 6. Responsive Web Applications
Explored how AI can generate mobile-friendly and modern HTML applications.

---

## 🚀 Outcome

Successfully created a fully interactive **Personal Environmental Health Analyzer Dashboard** using Claude, featuring:

- Environmental Health Score
- AQI Analysis
- Pollution Comparisons
- City Rankings
- Health Risk Assessment
- Personalized Recommendations
- Interactive Filters & Charts
- Responsive Dark-Themed UI

---

## 💡 Reflection

This challenge demonstrated how AI can combine **data analysis, visualization, health insights, and frontend development** into a single workflow. It showcased the power of prompt engineering for creating real-world analytical applications without building everything manually from scratch.

---

### #60DaysOfAI #Day8 #ClaudeAI #EnvironmentalHealth #DataAnalytics #DashboardDesign #AIProjects #FrontendDevelopment #DataVisualization #LearningInPublic
