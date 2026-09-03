# 🚗 Uber Ride & Booking Analysis | Power BI

An interactive **Power BI dashboard** built to analyze Uber booking performance, revenue, ride distance, vehicle contribution, booking outcomes, ratings, and location demand.

The project uses **150K+ booking records** from 2025 to identify operational patterns, revenue trends, vehicle performance, customer/driver experience, and booking losses.

---

## 📊 Project Overview

The dashboard provides a consolidated view of Uber's ride and booking performance through interactive KPIs, time-based analysis, vehicle-level comparisons, booking-status breakdowns, ratings, and top pickup/drop locations.

![Power BI](Images/Uber-Data-Analysis-0002.jpg)

### Key Business Questions

* How many bookings were completed vs. lost?
* How much revenue was generated?
* How does booking performance change by month and quarter?
* Which vehicle types contribute the most revenue?
* What are the busiest pickup and drop locations?
* How do rider and driver ratings compare?
* What proportion of bookings are cancelled, incomplete, or unsuccessful?
* How does ride distance vary across the business?

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard development, visualization & reporting
* **DAX** – KPI calculations and business measures
* **Power Query** – Data transformation and preparation
* **Microsoft Excel** – Source data

---

## 📌 Key Metrics

| KPI                           |       Value |
| ----------------------------- | ----------: |
| Total Bookings                | **150,000** |
| Completed Bookings            |  **93,000** |
| Lost / Non-Completed Bookings |  **57,000** |
| Revenue                       | **₹51.85M** |
| Total Distance                |   **2.51M** |
| Average Ride Distance         |   **24.64** |
| Average Rider Rating          |    **4.40** |
| Average Driver Rating         |    **4.23** |

### Booking Outcome

* **62%** – Completed
* **25%** – Cancelled by Customer / Driver
* **13%** – Incomplete / No Driver Found

---

## 📈 Dashboard Analysis

### 1. Booking & Revenue Trends

The dashboard tracks booking volume and revenue across **months and quarters**.

**Quarterly performance:**

| Quarter | Bookings | Completed | Revenue |
| ------- | -------: | --------: | ------: |
| Q1      |   37,507 |    23,273 | ₹13.07M |
| Q2      |   37,417 |    23,294 | ₹12.90M |
| Q3      |   37,781 |    23,248 | ₹12.80M |
| Q4      |   37,295 |    23,185 | ₹13.08M |

The quarterly analysis shows relatively consistent booking volumes throughout the year, with **Q1 and Q4 generating the highest revenue**.

---

### 2. Vehicle Performance

Revenue and booking contribution were analyzed across vehicle types.

| Vehicle Type  | Bookings | Revenue |
| ------------- | -------: | ------: |
| Auto          |   37,419 | ₹12.88M |
| Go Mini       |   29,806 | ₹10.34M |
| Go Sedan      |   27,141 |  ₹9.37M |
| Bike          |   22,517 |  ₹7.84M |
| Premier Sedan |   18,111 |  ₹6.28M |
| eBike         |   10,557 |  ₹3.62M |
| Uber XL       |    4,449 |  ₹1.53M |

**Auto** generated the highest booking volume and revenue contribution among the vehicle types.

---

### 3. Booking Status Analysis

The dashboard separates bookings into completed, cancelled, incomplete, and unsuccessful outcomes.

* **93K completed bookings**
* **37.5K cancelled bookings**

  * Customer cancellations
  * Driver cancellations
* **19.5K incomplete / no-driver bookings**
* **57K total non-completed bookings**

This highlights booking loss as an important operational area for improvement.

---

### 4. Location Analysis

Top pickup and drop locations were identified based on **completed booking count**.

**Top Pickup Locations**

1. Khandsa – 600
2. Barakhamba Road – 594
3. Subhash Chowk – 582
4. Madipur – 579
5. Mehrauli – 574

**Top Drop Locations**

1. Ashram – 592
2. Preet Vihar – 589
3. Sultanpur – 584
4. Noida Extension – 579
5. Dwarka Mor – 574

These locations provide a view of areas with consistently high completed-ride demand.

---

### 5. Ratings Analysis

The dashboard tracks both sides of the ride experience:

* **Average Rider Rating:** 4.40
* **Average Driver Rating:** 4.23

This allows performance monitoring from both customer and driver perspectives.

---

## 📊 Power BI Features Used

* KPI Cards
* Area Charts
* Column Charts
* Bar Charts
* Donut Charts
* Multi-row Cards
* Date Slicers
* Vehicle Type Filters
* Interactive filtering
* DAX Measures
* Conditional visual filtering
* Drill-oriented dashboard navigation

---

## 💡 Key Insights

* Uber processed **150K bookings**, with **93K successfully completed**.
* Approximately **38% of bookings were non-completed**, indicating a significant opportunity to reduce cancellations and unsuccessful bookings.
* **Auto** was the strongest vehicle category by both booking volume and revenue.
* Booking demand remained relatively stable across quarters.
* **Q1 and Q4** recorded the highest quarterly revenue.
* Rider ratings were higher than driver ratings, at **4.40 vs. 4.23**.
* Location-level analysis highlights specific pickup and drop zones with consistently high completed-booking demand.

---

## 🎯 Business Value

This dashboard can support operational and commercial decision-making by helping teams:

* Monitor booking and revenue performance
* Identify booking-loss patterns
* Compare vehicle-level contribution
* Track customer and driver experience
* Identify high-demand locations
* Analyze monthly and quarterly trends
* Prioritize opportunities to improve booking completion

---

## 📁 Project Structure

```text
Uber-Ride-Booking-Analysis/
│
├── Uber Raw Data.xlsx
├── Uber Data Analysis.pbix
└── README.md
```

---

## 🚀 Conclusion

The project demonstrates how **Power BI, DAX, Power Query, and Excel** can be combined to transform raw ride-booking data into an interactive business intelligence solution.

The analysis focuses not only on reporting KPIs but also on identifying **booking losses, revenue drivers, vehicle contribution, customer/driver experience, and demand patterns** that can support data-driven operational decisions.
