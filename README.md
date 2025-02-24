# 🗳️ Campaign Finance Data Analysis

## Overview
This project aims to analyze campaign finance data from the past five years (2019-2023) in Washington State, providing valuable insights into political contributions, expenditures, and financial trends across different parties and regions. The project features a comprehensive visual analytic dashboard that highlights key metrics and patterns in campaign finance.

---

## 📊 Project Objectives

1. **Explore Campaign Finance Trends:** Analyze campaign finance trends over multiple election cycles.
2. **Evaluate Financial Efficiency:** Compare contributions against expenditures to identify patterns of effective or wasteful spending.
3. **Visualize Regional Contributions:** Map financial activity across different regions to identify hotspots of contributions.
4. **Assess Party Dominance:** Analyze which political parties receive the most support and dominate fundraising efforts.
5. **Predict Future Trends:** Forecast financial contributions based on historical data to identify growth opportunities.

---

## 📂 Data Source & Description

The data used for this project is sourced from the [Washington State Campaign Finance Summary](https://data.wa.gov/Politics/Campaign-Finance-Summary/3h9x-7bvm/about_data). It includes summarized information about candidate campaigns and political committees by election year.

Key attributes of the dataset include:
- **election_year:** Year of the election.
- **filer_name:** Name of the filer (candidates or committees).
- **committee_city, committee_state, committee_county:** Geographic data for regional analysis.
- **office:** The office being contested (e.g., senator, governor).
- **party:** The political party associated with the filer.
- **contributions_amount:** Total contributions received.
- **expenditures_amount:** Total spending by campaigns or committees.
- **loans_amount:** Loans taken by campaigns or committees.
- **independent_expenditures_for_amount:** Supportive independent expenditures.
- **independent_expenditures_against_amount:** Opposing independent expenditures.
- **position:** The position being contested.

---

## 📈 Dashboards & Visualizations

### 1. Overview Dashboard
- **Geographic Distribution:** Map highlighting campaign financial activity across regions.
- **Yearly Trends:** Line chart showing year-over-year (YoY) growth and decline in contributions.
- **Contributions by Party:** Bar chart comparing contributions received by different political parties.
- **Contributions vs. Expenditures:** Area chart comparing campaign spending efficiency across regions.

### 2. Contributions Dashboard
- **Party Efficiency Comparison:** Grouped bar chart comparing financial activity and cost-effectiveness across parties and regions.
- **Efficiency Score Analysis:** Horizontal bar chart showing ROI for different committee categories.
- **Monthly Burn Rate:** Vertical bar chart highlighting monthly expenditures by committee category.

### 3. Efficiency Dashboard
- **Contribution by Party and Region:** Bar chart showing contributions across parties and regions.
- **Party Contributions Dominance:** Bubble chart visualizing party dominance in terms of contributions.
- **Growth Analysis:** Scatter plot comparing financial growth trends over time.

---

## 🔍 Insights & Analysis

- **Regional Analysis:** Identify regions with the highest financial activity and correlate them with campaign success.
- **Temporal Trends:** Analyze which election years saw the most significant growth or decline in contributions.
- **Party Comparison:** Determine which parties received the most support and whether larger parties dominate fundraising.
- **Spending Efficiency:** Evaluate which campaigns are maximizing contributions with minimal wastage.

---

## 📊 Predictive Analysis
- Conducted trend analysis to identify patterns in campaign contributions over multiple election cycles.
- Highlighted growth opportunities by forecasting future financial contributions based on historical data.

---

## 🛠️ Key Features

1. **Interactive Visualizations:** Users can filter by region, party, or contribution category for in-depth analysis.
2. **Calculated Fields:** Efficiency scores, ROI, and year-over-year growth percentages were computed for detailed insights.
3. **Advanced Visualizations:** Bubble charts, scatter plots, and geographic maps provide intuitive ways to explore campaign finance data.
4. **Dynamic Updates:** All charts and dashboards update dynamically based on user input, enhancing data exploration.

---

## 💻 Technologies Used

- **Data Source:** Washington State Campaign Finance Data
- **Tools:** Tableau, Python, Excel
- **Visualization Libraries:** Matplotlib, Seaborn

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Open the Tableau Dashboard:**
   - Use Tableau Desktop to open the `.twbx` file and explore the visualizations.

3. **Analyze Data Files:**
   - Explore CSV and Excel files for detailed campaign finance data.

---

## 🤝 Contributions

We welcome contributions to improve the insights and expand the scope of this project. To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---

By providing a comprehensive view of campaign finance data, this project aims to enhance transparency and understanding of political contributions, enabling stakeholders to make data-driven decisions.
