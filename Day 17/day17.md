# Day 17 – AI-Powered Fuel Analytics Dashboard

## Objective

Build an interactive fuel analytics dashboard that compares the real-world cost, emissions, maintenance, and long-term ownership impact of different fuel types using AI-generated insights.

The goal was to understand how data visualization and AI can help users make smarter vehicle ownership decisions.

---

## Tools Used

* Claude AI
* Prompt Engineering
* HTML
* CSS
* JavaScript
* SVG Charts
* GitHub

---

## Problem Statement

Choosing a fuel type based only on pump price can be misleading.

Factors such as mileage, maintenance cost, refueling time, vehicle age, and emissions significantly impact the total cost of ownership.

This project analyzes these factors to identify the most practical fuel option for a vehicle owner.

---

## Vehicle Details

| Parameter        | Value         |
| ---------------- | ------------- |
| Vehicle          | Vitara Brezza |
| Current Fuel     | Petrol (E20)  |
| Vehicle Age      | 5 Years       |
| Usage Type       | Mixed         |
| Monthly Distance | 140 km        |

---

## Fuel Types Compared

* Petrol (E20)
* Diesel
* CNG
* Electric Vehicle (EV)
* E85 (Flex-Fuel)

---

## Metrics Analyzed

* Average Fuel Cost per Kilometer
* Average CO₂ Emissions per Kilometer
* Average Maintenance Cost per Kilometer
* Average Refuel/Recharge Time
* Fuel Efficiency Trends by Vehicle Age
* Monthly Running Cost
* Long-Term Cost of Ownership
* E85 Break-Even Analysis

---

## Key Calculations

### Average Cost per Kilometer

```text
Fuel Cost ÷ Distance Travelled
```

### Average CO₂ Emissions per Kilometer

```text
CO₂ Emitted ÷ Distance Travelled
```

### Average Maintenance Cost per Kilometer

```text
Maintenance Cost ÷ Distance Travelled
```

### E85 Pump Savings

```text
((Petrol Price − E85 Price) ÷ Petrol Price) × 100
```

### E85 Running Penalty

```text
((E85 Cost/km − Petrol Cost/km) ÷ Petrol Cost/km) × 100
```

### E85 Break-Even Price

```text
(E85 Mileage ÷ Petrol Mileage) × Petrol Price
```

---

## Dashboard Features

* Responsive 1080 × 1350 layout
* Glassmorphism UI design
* Interactive SVG charts
* KPI summary cards
* Cost comparison by fuel type
* CO₂ emissions visualization
* Vehicle age trend analysis
* Animated E85 score gauge
* Fuel recommendation cards
* Data-driven verdict section

---

## Key Insights

* Petrol (E20) offered the best balance of cost, convenience, and availability for the selected usage pattern.
* E85 appeared cheaper at the pump but resulted in a higher running cost due to reduced mileage.
* EVs showed the lowest cost per kilometer and emissions but required charging infrastructure.
* CNG remained a cost-effective option for high-mileage city usage.
* Diesel performed well for long-distance driving despite higher maintenance costs.

---

## The E85 Paradox

> Lower fuel price does not always mean lower running cost.

Although E85 was approximately 18% cheaper per litre, its lower mileage increased the overall cost per kilometer by 2.6% compared to Petrol.

This highlighted the importance of evaluating total ownership cost rather than focusing only on pump prices.

---

## What I Learned

* AI can automate complex data analysis workflows.
* Data storytelling improves decision-making.
* Prompt engineering enables rapid dashboard generation.
* Visualizations simplify multi-variable comparisons.
* Real-world insights require context beyond raw numbers.

---

## Future Improvements

* Add real-time fuel price APIs
* Support multiple vehicle models
* Include annual ownership cost forecasting
* Add downloadable PDF reports
* Integrate route-based fuel recommendations

---

## Conclusion

This project demonstrated how AI, data analytics, and interactive dashboards can transform raw transportation data into actionable insights.

Instead of relying on assumptions, users can make informed decisions using data-driven comparisons.

> "The cheapest option isn't always the most economical—context and data matter."

---

## Disclaimer

This dashboard is created for educational and analytical purposes only.

Actual costs may vary depending on fuel prices, driving conditions, vehicle maintenance, and regional factors.

---

#Day17 #ClaudeAI #FuelAnalytics #DataVisualization #PromptEngineering #DashboardDesign #LearningInPublic #ArtificialIntelligence
