# Uber Ride Performance Dashboard (Tableau Analytics)

An interactive data visualization project built using Tableau to analyze Uber ride performance, booking trends, and operational metrics. This dashboard translates complex ride data into actionable business intelligence to optimize operations and improve customer satisfaction.

## Dashboard Visualizations & Key Metrics

The dashboard provides a comprehensive view of operational performance through four primary sections:

*   **Total Bookings Trend (2024):** Tracks monthly booking volumes (totaling over 92,000+ bookings) to identify seasonal demand patterns, peak months (such as January, March, and July), and low-volume periods.
*   **Average Customer Rating by Vehicle Type:** Monitors user satisfaction across various services (eBike, Go Sedan, Auto, Bike, Premier Sedan, Uber XL, Go Mini), showcasing consistent service quality with ratings hovering around 2.7 to 2.8 stars.
*   **Average CTAT (Customer Turnaround Time):** Analyzes the efficiency of dispatches and arrivals across vehicle types, maintaining a stable baseline of approximately 29 minutes per trip.
*   **Top Reasons for Customer Cancellations:** Highlights core operational pain points. "Driver Delayed" and "Wrong Address" emerge as the leading drivers for trip cancellations, signaling specific areas for process improvement.
*   **Bookings by Payment Method:** Breaks down transaction preferences, revealing UPI and Cash as the most dominant payment channels used by customers.

##  Tools & Technologies Used

*   **Data Analysis:** Python (Jupyter Notebook - `Uber.ipynb`)
*   **Data Visualization:** Tableau Desktop (`Uber_Dash.twb`)
*   **Data Source:** Cleaned trip logistics dataset (`uber_cleaned.csv` containing 92,392 rows)

##  Key Business Insights Derived

1.  **Demand Stability:** Booking numbers stay consistently high throughout the year, requiring robust driver supply management during predictable peak months like March and July.
2.  **Addressing Cancellation Bottlenecks:** Since driver delays and wrong addresses account for the majority of customer cancellations, optimizing the in-app navigation and driver matching algorithms could significantly reduce lost revenue.
3.  **Digital Payment Dominance:** The heavy reliance on UPI indicates a smooth digital checkout experience, though operational cash management remains vital due to the high volume of cash trips.

---

