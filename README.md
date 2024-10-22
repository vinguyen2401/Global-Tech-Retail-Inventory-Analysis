
# Project Title: Global-Tech-Retail-Inventory-Analysis Using ABC-XYZ Classification
This is a self-initiated project to practice inventory analysis based on a dataset from Kaggle
## Project Background
The goal of this project is to optimize inventory management processes for a retail company by applying the **ABC-XYZ classification methodology**. This approach aims to balance stock levels across varying value and demand profiles, primarily focusing on reducing holding costs while ensuring adequate stock for high-value and consistently demanded products.

By classifying products into high-value (A), medium-value (B), and low-value (C) categories based on their contribution to sales revenue, combined with their demand variability (X = consistent, Y = variable, Z = uncertain), the company seeks to streamline operations and enhance profitability. This analysis utilizes historical inventory and demand data from **2019**, offering insights into stock optimization across these categories. Given the dynamic market conditions, recommendations will address both immediate actions and long-term strategic improvements, including advanced demand forecasting techniques.

## Data Structure
![Global Tech Data Model](https://github.com/vinguyen2401/Global-Tech-Retail-Inventory-Analysis/blob/main/Global%20Tech%20Data%20Model.png?raw=true)
## Inventory Dashboard
The following image showcases a sample of the inventory dashboard created to visualize key metrics and insights derived from the data analysis.

![Inventory Dashboard Sample](https://github.com/vinguyen2401/Global-Tech-Retail-Inventory-Analysis/blob/main/Inventory%20Dashboard%20Sample%20(1).jpg?raw=true)

## Approach
The **ABC-XYZ classification model** was applied to categorize inventory based on:
- **ABC Classification**: Evaluates relative value contribution.
- **XYZ Classification**: Assesses demand variability.

This targeted approach facilitates stock level adjustments, balancing high-value and high-demand items with those exhibiting uncertainty or lower sales potential. By analyzing stock distribution across these categories, the project identifies immediate inventory optimization opportunities and suggests strategic enhancements for future demand forecasting and stock management.

### Definitions
- **ABC Classification**:
  - **A (High Value)**: Items contributing most to sales revenue (approx. 70% of revenue from 20% of products).
  - **B (Medium Value)**: Items contributing moderately (around 20% of sales).
  - **C (Low Value)**: Items contributing the least, with many SKUs but lower overall sales impact (approx. 10% of revenue from 50% of SKUs).
  
- **XYZ Classification**:
  - **X (Uniform Demand)**: Products with consistent demand patterns.
  - **Y (Variable Demand)**: Products with fluctuating demand influenced by seasonality or other factors.
  - **Z (Uncertain Demand)**: Products with unpredictable demand, posing risks of overstocking or understocking.

## Insights Deep Dive

### Inventory Classification
The ABC-XYZ classification system has been effectively utilized to categorize products, providing critical insights into stock management strategies.

- **A Category (High Value Items)**:
  - **Contribution**: Comprising only 20% of total SKUs, A items generate approximately 69% of total sales revenue, highlighting their significance.
  - **Management Strategy**: Effective management is crucial to avoid stockouts. Implementing **Just-In-Time (JIT)** inventory practices will help maintain optimal stock levels and minimize carrying costs.
  - **Risk Assessment**: Regular reviews of sales data for A items can facilitate adjustments in order quantities to align with demand.

- **B Category (Medium Value Items)**:
  - **Contribution**: Representing 30% of SKUs and contributing 21% to total sales, B items risk obsolescence due to overrepresentation in inventory.
  - **Management Strategy**: A dynamic inventory approach is recommended, combining JIT practices with safety stock for unpredictable fluctuations.
  - **Risk Assessment**: Monitoring demand patterns for B items, particularly in seasonal contexts, is essential to optimize inventory levels.

- **C Category (Low Value Items)**:
  - **Contribution**: Despite making up 50% of total SKUs, C items contribute only 10% to sales, leading to overstocking risks.
  - **Management Strategy**: A rigorous inventory reduction plan is necessary, involving the analysis of sales velocity and potential phasing out of slow-moving products.
  - **Risk Assessment**: Continuous performance assessments of C items will help identify candidates for clearance or discontinuation, reducing holding costs.

### Inventory Turnover Ratio
The **inventory turnover ratio** measures how quickly inventory is sold and replaced over a specified period.

- **High Turnover Rate**: Indicates effective inventory management and strong sales performance, especially for A category items.
- **Low Turnover Rate**: Observed in B-Z and C-Z categories, signaling potential overstocking and sales underperformance, leading to increased holding costs.
- **Actionable Insights**: The company should aim to improve turnover rates for B and C items through targeted marketing and promotional strategies. Adjusting reorder policies and utilizing historical sales data can enhance inventory efficiency.

### Stock Status Classification
This classification categorizes products based on demand variability, highlighting items needing immediate attention.

- **A-X (High Value, Uniform Demand)**:
  - **Current Stock Levels**: 4.04M units maintained, indicating stable demand.
  - **Management Strategy**: Automating replenishment will ensure availability while maintaining lean inventory levels.

- **A-Y (High Value, Variable Demand)**:
  - **Current Stock Levels**: 10.61M units require careful management.
  - **Management Strategy**: Utilizing advanced analytics and machine learning for demand predictions can help align stock levels with sales trends.

- **B-Z (Medium Value, Uncertain Demand)**:
  - **Current Stock Levels**: 27.35M units suggest potential overstocking.
  - **Management Strategy**: Immediate reduction strategies, such as promotional activities or phasing out low-demand SKUs, are essential.

- **C-Z (Low Value, Uncertain Demand)**:
  - **Current Stock Levels**: Holding 18.02M units is unsustainable.
  - **Management Strategy**: A drastic approach, including liquidation of excess stock and reassessment of product lines, is necessary.
  

## Key Recommendations
1. **Reduce Overstock** in B-Z and C-Z Categories: Implement aggressive promotional strategies and assess product relevance.
2. **Lean Inventory Management** for A-X Items: Automate replenishment and maintain optimal stock levels for high-value items.
3. **Enhance Demand Forecasting Techniques**: Invest in predictive analytics tools to improve forecasting accuracy for fluctuating demand items.

## Assumptions and Caveats
- **Data Validity**: The analysis relies on 2019 historical data, which may not reflect current market trends. Regular re-evaluation of inventory strategies based on up-to-date sales data is critical.
- **Demand Forecasting Limitations**: Z and Y categories face uncertainty in demand predictions; leveraging real-time data and machine learning can enhance forecasting accuracy.
- **Financial Impact of Overstocking**: Addressing overstocking promptly will mitigate holding costs and free up working capital, enhancing operational efficiency.

## Conclusion
Leveraging insights from the ABC-XYZ classification and inventory turnover analysis, this project proposes targeted strategies to optimize inventory management and enhance profitability for the company.

