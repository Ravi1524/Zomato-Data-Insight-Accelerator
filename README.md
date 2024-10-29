# Zomato-Data-Insight-Accelerator

## Project Overview
You have just joined the analytics team at Zomato, one of India's leading food delivery platforms. This project involves analyzing sales data to identify key metrics that can improve customer experience and drive growth. The company is facing challenges such as declining customer satisfaction, increasing order cancellations, and inconsistent sales performance across regions. Your mission is to uncover insights from the data that will help address these challenges.

## Objective
The primary objective of this project is to identify the factors driving customer dissatisfaction, leading to increased order cancellations and reduced customer retention. You will also provide actionable insights to guide Zomato's decision-making for improving delivery efficiency, customer engagement, and operational efficiency.

## Stakeholders
### Internal Stakeholders:
- Marketing Team: Responsible for customer retention strategies.
- Operations Team: Manages the delivery fleet and works to reduce delivery times.
- Customer Support: Handles customer complaints, including refunds and cancellations.
- Executive Leadership: Needs a summary of findings for high-level decisions.

### External Stakeholders:
- Customers: Their satisfaction drives Zomato’s revenue and brand loyalty.
- Restaurant Partners: Their performance affects customer satisfaction and order preparation speed.

## Data Description
The dataset used for this analysis contains:
- **Order Data**: Order details, including order date, amount, and delivery time.
- **Customer Data**: Information about customer ratings and demographics.
- **Restaurant Data**: Details about the restaurant, cuisine type, and performance ratings.

### Data Dictionary
| Column Name         | Data Type | Description                                      |
|---------------------|-----------|--------------------------------------------------|
| Order_ID            | String    | Unique identifier for each order                 |
| Customer_ID         | String    | Unique identifier for each customer              |
| Order_Date          | Date      | Date and time when the order was placed          |
| Restaurant_ID       | String    | Unique identifier for each restaurant            |
| Restaurant_Name     | String    | Name of the restaurant                           |
| Cuisine_Type        | String    | Type of cuisine (e.g., Indian, Chinese, Italian) |
| Order_Amount        | Float     | Total amount spent on the order                  |
| Delivery_Fee        | Float     | Fee charged for delivery                         |
| Total_Amount        | Float     | Final amount paid (Order_Amount + Delivery_Fee)  |
| Payment_Method      | String    | Method of payment (e.g., Credit Card, Cash)      |
| Discount_Amount     | Float     | Discount applied to the order                    |
| Order_Status        | String    | Status of the order (e.g., Completed, Cancelled) |
| Delivery_Time       | Integer   | Time taken for delivery (minutes)                |
| Customer_Rating     | Integer   | Customer rating of the order (1 to 5 scale)      |
| City                | String    | City in which the order was placed               |
| Restaurant_Rating   | Float     | Average restaurant rating (1 to 5 scale)         |
| Number_of_Items     | Integer   | Number of items in the order                     |
| Order_Type          | String    | Type of order (e.g., Delivery, Dine-in)          |

## Analysis Questions & Visualizations
1. **Total Number of Completed Orders**: Filter by `Order_Status = "Completed"` and visualize using a Scorecard.
2. **Average Delivery Time Across All Cities**: Filter by completed orders and visualize with a Bar Chart.
3. **Most Used Payment Method**: Group by `Payment_Method` and visualize with a Pie Chart.
4. **Revenue Trend Over Time**: Sum `Total_Amount` and group by `Order_Date` using a Time Series Chart.
5. **Top Revenue-Generating Cities**: Group by `City` and sum `Total_Amount` using a Geo Map.
6. **Customer Rating Distribution**: Visualize distribution with a Histogram.
7. **Cuisine Type with Highest Average Order Value**: Group by `Cuisine_Type` and visualize with a Column Chart.
8. **Total Delivery Time by Order Status**: Use a Stacked Bar Chart to compare.
9. **Delivery Times by Cuisine Type**: Group by `Cuisine_Type` and visualize with a Heat Map.
10. **Average Number of Items by Payment Method**: Group by `Payment_Method` and visualize with a Treemap.

## Key Findings
- **Delivery Delays and Cancellations**: Fluctuating delivery times and high cancellation rates are negatively impacting customer satisfaction.
- **Inconsistent Restaurant Performance**: Variability in restaurant ratings contributes to a poor customer experience.

## Recommendations
- **Optimize Delivery Efficiency**: Improve logistics to reduce delivery delays.
- **Customer Engagement**: Implement targeted campaigns to retain customers and reduce cancellations.
- **Restaurant Incentives**: Reward high-performing restaurants and address underperforming ones.

## Tools & Technologies
- **Data Visualization**: Tableau
- **Data Management**: Google Sheets, Excel
  
## Connect with the Project Lead
**Ravi Kumar**  
[LinkedIn Profile](https://www.linkedin.com/in/ravi-kumar-28a905256)

## Resources
- **Dashboard Link**: https://lnkd.in/gtmpzadK

## Dashboard Snapshot
![Screenshot (84)](https://github.com/user-attachments/assets/66e4df4e-1c66-4d42-be94-e7bc44b26aeb)
