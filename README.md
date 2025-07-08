# Global-Superstore - Shipment Analysis

This project presents a shipment performance analysis using interactive dashboards built from the Global Superstore dataset.

---

## Global Superstore Dashboards

---

### 1. Shipments Delivery Analysis

![Shipments Delivery Analysis](Images/ShipmentsDeliveryAnalysis.png)

#### a. Key Visualizations

1. **KPI Tiles (Top Row)**: Highlight key performance indicators and summary statistics.  
2. **Line Chart – Delayed Orders Ratio Over Time**: Illustrates monthly trends in delivery delays with annotations.  
3. **Map – Delivery Status by Country**: Shows on-time vs. delayed shipments globally using color coding.  
4. **Bar Chart – Average Delivery Time by Region and Status**: Compares delivery time across regions for on-time (green) and delayed (red) orders.  
5. **Interactivity**: Filters, parameters, conditional highlighting, and navigation features enhance user experience.

#### b. Interpretation

1. **KPI Insight**: 82% of shipments are on time. However, nearly 1 in 5 are delayed. The average delivery time is 4.0 days.  
2. **Trend Fluctuations**: Delay spikes occur seasonally or due to operations. The highest delay (24%) was in Mar-13; the lowest (~12%) in Nov-13 and Mar-11.  
3. **Regional View**: China has significant delays—logistics or supplier issues could be contributing factors.  
4. **Regional Performance**: Central and South regions face longer delays, while EMEA and North America show better performance.

#### c. Strategic Recommendations

1. **Optimize High-Delay Regions**: Prioritize operational reviews in China and Central region. Investigate last-mile logistics, customs delays, or switch to alternative vendors.  
2. **Predict & Prevent Delays**: Analyze delay spikes (e.g., March & July). Use forecasting and predictive analytics to prevent future disruptions.  
3. **Improve Standards**: Reduce delivery time from 4.0 to <3.5 days to increase competitiveness.  
4. **Customer Communication**: Notify customers in high-delay zones proactively. Offer incentives for flexible delivery options.

---

### 2. Shipments Performance Analysis

![Shipments Performance Analysis](Images/ShipmentsPerformanceAnalysis.png)

#### a. Key Visualizations

1. **Shipments by Priority (Heatmap Table)**: Shows order counts across shipment priorities and markets.  
2. **Priority vs Avg Shipping Days and Cost (Pie Chart)**: Compares average delivery time and cost for each priority.  
3. **Delivery Status by Market (Donut Charts)**: Visualizes shipment performance across markets.

#### b. Interpretation

1. **Order Priority Trends**: Most shipments are Medium priority (57%); Critical shipments are only 6.6%. APAC leads in volume across all levels.  
2. **Cost vs Speed**: Critical shipments are fastest (1.8 days) but most expensive. Low priority takes longest (6.5 days) and oddly costs more than Medium.  
3. **Market Performance**: Canada performs best (65% on-time), but volume is low. LATAM and EU face the most delays (~41%). No market exceeds 66% on-time rate.

#### c. Strategic Recommendations

1. **Improve On-Time Delivery**: Focus on LATAM and EU. Enforce vendor SLAs, analyze root causes, and improve ETA accuracy.  
2. **Rethink Low Priority Logistics**: Low priority is inefficient. Audit partners, reduce costly re-routing, and consolidate loads.  
3. **Control High-Cost Shipping**: Critical shipments should be limited to urgent cases. Add approval controls for high-cost deliveries.  
4. **Tailor Regional Strategies**: APAC needs scaling and warehouse automation. Use Canada’s high on-time rate as a model.

---
