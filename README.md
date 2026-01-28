# Shopping Behavior Analysis: Who Spends, When, and on What?

## 📊 Project Overview

This project analyzes customer shopping patterns to uncover insights about spending behavior, seasonal preferences, and product trends. Using a dataset of 3,900 customer records with 18 features, I explored two key business questions:

1. **Which customers spend the most?**
2. **How do preferences change throughout the seasons?**

The analysis reveals actionable insights for marketing strategies, inventory management, and seasonal product planning that can directly impact revenue and customer engagement.

---

## 🎯 Key Findings

### 💰 Spending Increases with Age

<img width="906" height="380" alt="image" src="https://github.com/user-attachments/assets/2ba45b65-d6f3-4b40-8083-ad120e3063de" />


Older customers drive the highest revenue:
- **60+ and 50-59 age groups** generate the most spending (~$46.5k to ~$46.9k)
- **20-49 age groups** contribute moderately (~$43k to ~$44k)
- **Under 20** represents an outlier with significantly lower spending (~$9k)

**Business Impact:** Marketing strategies should prioritize high-value age segments. Older generations respond better to email campaigns, while younger customers engage more effectively through social media.

---

### 🌦️ Seasonal Product Preferences Shift Dramatically

<img width="902" height="256" alt="image" src="https://github.com/user-attachments/assets/8b5e6987-4440-4cd4-a882-fe317bf55f5d" />


The top-selling product category rotates with each season:
- **Fall:** Jackets lead sales
- **Spring:** Sweaters dominate (unexpectedly, despite warmer weather)
- **Summer:** Pants are most popular
- **Winter:** Sunglasses take the lead

**Business Impact:** These trends enable strategic inventory management and seasonal promotional planning. Businesses can create targeted seasonal bundles to maximize sales during peak demand periods.

---

### 🎨 Color Preferences Are Seasonal

<img width="729" height="509" alt="image" src="https://github.com/user-attachments/assets/0b28aaef-9487-4236-a20d-3f655cf15dda" />


Color popularity varies dramatically across seasons:
- Colors shift between ranking 12th in one season to #1 in another
- Example: **Green** ranks 12th in Fall ($2.5k) but jumps to #1 in Winter ($3.1k)
- Each season shows distinct color spending patterns

**Business Impact:** Seasonal color insights can inform product design and limited-edition releases. Strategic color selection drives customer attraction and increases profitability during specific seasons.

---

## 💡 Business Recommendations

Based on the analysis, I recommend three strategic initiatives:

### 1. **Age-Based Marketing Focus**
Target high-value customers (50-59 and 60+) with email promotions and personalized campaigns. These segments consistently generate the highest revenue and warrant priority in marketing budgets.

### 2. **Seasonal Inventory & Promotion Planning**
Align inventory levels and promotional campaigns with seasonal product trends:
- Stock sweaters for Spring campaigns
- Promote jackets during Fall
- Feature sunglasses in Winter marketing

### 3. **Limited-Edition Seasonal Colors**
Launch color-specific product lines matched to seasonal preferences. Create urgency with limited-availability seasonal colors to boost appeal and drive higher conversion rates.

---

## 🛠️ Technical Details

### Dataset
- **Source:** [Kaggle Shopping Behaviors Dataset](https://www.kaggle.com/datasets/zubairamuti/shopping-behaviours-dataset)
- **Size:** 3,900 rows × 18 features
- **Categories:**
  - Customer Demographics (Age, Gender, Location)
  - Product Details (Item, Category, Size, Color, Season)
  - Shopping Behavior (Purchase Frequency, Subscription Status, Discount Usage)
  - Customer Feedback (Review Ratings)

### Tools & Technologies
- **Python** - Data analysis and visualization
- **Pandas** - Data manipulation and aggregation
- **Plotly** - Statistical visualizations
- **Jupyter Notebook** - Interactive analysis environment

### Analysis Approach

**1. Data Exploration**
- Loaded and cleaned 3,900 customer records
- Examined distributions across demographics and product categories
- Identified missing values and data quality issues

**2. Customer Segmentation**
- Grouped customers by age brackets (<20, 20-29, 30-39, 40-49, 50-59, 60+)
- Calculated total spending per segment
- Analyzed purchasing patterns across demographics

**3. Seasonal Analysis**
- Aggregated orders by season (Spring, Summer, Fall, Winter)
- Identified top product categories per season
- Analyzed color spending patterns across seasonal periods

**4. Visualization**
- Created bar charts for age-based spending comparison
- Designed seasonal product popularity charts
- Built treemaps for hierarchical color spending analysis
- Applied custom color palettes optimized for accessibility

### Key Metrics Calculated
- Total spending by age group
- Order frequency by product category and season
- Revenue distribution by color across seasons
- Customer segmentation patterns

---

## 📁 Repository Contents

```
ShoppingBehaviorAnalysis/
│
├── shoppingBehaviorFinal.ipynb          # Complete analysis notebook
├── 4122_CustomerSpending.pdf             # Visual insights report
├── 4122_CustomerSpendingTechnicalReport.pdf  # Technical documentation
└── README.md                             # This file
```

---

## 🚀 How to Use This Project

### Prerequisites
```bash
pip install pandas plotly jupyter
```

### Running the Analysis
1. Clone this repository
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/zubairamuti/shopping-behaviours-dataset)
3. Open `shoppingBehaviorFinal.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis
5.**Interact with the visualizations!** Hover over data points, zoom in on specific areas, and pan across charts to explore patterns in detail

---

## 📈 Future Enhancements

Potential directions to extend this analysis:
- Predictive modeling for customer lifetime value
- Recommendation system based on seasonal preferences
- Geographic analysis of regional shopping patterns
- Time-series forecasting for inventory optimization
- Customer churn analysis using subscription status


---

## 📝 Important Note

These trends reflect patterns specific to this dataset and should not be overgeneralized. Results should be validated with additional data sources before implementing large-scale business decisions.

---

*This project demonstrates the application of data analytics to drive strategic business decisions in retail and e-commerce.*
