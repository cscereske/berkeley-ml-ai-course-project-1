# Coupon Acceptance Analysis
**By Chris Cereske**

## Overview
This project is part of a practical application assignment designed to answer the question: **"Will a customer accept the coupon?"**. This project not only demonstrates technical skills in data analysis but also provides actionable insights into customer behavior for coupon-based promotions.

The work in this repository includes an exploration of survey data and a comparison of customer responses using statistical summaries and visualizations. The findings and recommendations are intended to help businesses understand customer preferences and optimize coupon campaigns.

## Data
The dataset for this analysis comes from the UCI Machine Learning Repository and was collected via a survey conducted on Amazon Mechanical Turk. The survey presents various driving scenarios and asks participants whether they would accept a coupon in each scenario. Key details about the dataset include:

- **Survey Responses**: 
  - "Right away" 
  - "Later, before the coupon expires"
  - "No, I do not want the coupon"

  The first two responses are labeled as `Y = 1` (accepted), while the third is labeled as `Y = 0` (rejected).

- **Coupon Types**:
  - Less expensive restaurants (under $20)
  - Coffee houses
  - Carryout and takeaway
  - Bars
  - More expensive restaurants ($20–$50)

The dataset contains variables such as destination, current time, weather, passenger, and more, providing rich context for understanding coupon acceptance behavior.

## Project Deliverables
The deliverables for this project include:

1. **Jupyter Notebook**:
   - A comprehensive analysis of the dataset using Python libraries such as `pandas`, `Matplotlib`, and `Seaborn`.
   - Statistical summaries comparing customers who accepted coupons (`Y = 1`) to those who rejected them (`Y = 0`).

2. **Visualization**:
   - Clear and informative visualizations that illustrate the differences in customer responses based on various attributes.

3. **Findings and Recommendations**:
   - A detailed section highlighting key insights from the analysis.
   - Actionable recommendations for businesses to enhance coupon campaign effectiveness.

4. **GitHub Repository**:
   - This repository serves as a portfolio project, showcasing the Jupyter Notebook, dataset, and this README file.

## Findings


### Bar Coupon Acceptance:

The strongest indicator of whether a driver will accept a bar coupon is their frequency of visiting bars.
Drivers who visit bars at least once per month are more likely to accept a bar coupon, as they are already inclined to visit a bar. However, a bar coupon is unlikely to influence someone to visit a bar if they do not already frequent them.

### Coffee House Coupon Acceptance:

Drivers who visit coffee houses more frequently are significantly more likely to accept coffee house coupons.
Time of day plays a crucial role in coupon acceptance for coffee houses. Morning and early afternoon, typical times for coffee consumption, show a much higher acceptance rate.

### Impact of Time:
Time of day has a substantial impact on coffee house coupon acceptance but has minimal influence on bar coupon acceptance.
Drivers are more likely to accept coffee house coupons if the time aligns with when they would naturally consume coffee.
General Insights:

### Impact of Habits:
Coupon acceptance is largely influenced by prior habits and behaviors, such as regular visits to bars or coffee houses.

## Recommendations
### Targeted Coupon Campaigns:

For bar coupons, focus marketing efforts on individuals who already frequent bars at least once per month. Give out coupons closer to bars where people who frequent bars may be.

For coffee house coupons, target drivers during morning and early afternoon hours to maximize coupon acceptance.
