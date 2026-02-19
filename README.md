# British Airways Customer Reviews Analysis Dashboard

## Project Overview
This project presents an interactive Tableau dashboard analyzing British Airways customer reviews across multiple dimensions such as time, geography, aircraft type, seat class, and service metrics. The primary goal is to uncover trends in customer satisfaction, identify operational strengths and weaknesses, and provide data-driven insights to support service improvements.

https://github.com/user-attachments/assets/4282c935-69fb-44b8-9242-5efe4242921f

## Key Features & Functionality
* **Interactive Filters:** Users can slice data by Metric (Overall rating, cabin staff, etc.), Date Range (March 2016 – October 2023), Seat Type, Traveler Type, Aircraft Type, and Continent.
* **Temporal Trends:** A time-series line chart tracks how customer satisfaction fluctuates by month, highlighting periods of disruption or improvement.
* **Geographical Mapping:** A world map visualizes regional service quality, helping identify specific routes with high or low satisfaction levels.
* **Aircraft Performance:** Bar charts compare ratings across different aircraft models, balanced by review volume to ensure statistical context.

## Service Metrics (Average Ratings)
| Category | Rating | Status |
| :--- | :--- | :--- |
| **Overall Rating** | 4.2 | Moderate |
| **Cabin Staff Service** | 3.3 | Relative Strength |
| **Ground Service** | 3.0 | Neutral |
| **Seat Comfort** | 2.9 | Needs Improvement |
| **Value For Money** | 2.8 | Needs Improvement |
| **Food & Beverages** | 2.4 | Weakness |
| **Entertainment** | 1.4 | Major Weakness |

## Key Insights 
* **Service Gaps:** Entertainment (1.4) and Food/Beverages (2.4) emerge as the strongest contributors to negative sentiment.
* **Fleet Variability:** Wide-body aircraft such as the Boeing 747-400 (4.7) and Boeing 787 (4.4) clearly outperform narrow-body models like the A321 (3.6).
* **Frontline Strength:** Despite ongoing challenges with the physical product, cabin crew service continues to stand out as a brand differentiator, achieving a relatively strong score of 3.3.

## Strategic Recommendations
* **Next-Generation IFE Upgrade:** Prioritize comprehensive hardware and UI/UX enhancements for In-Flight Entertainment systems across the long-haul fleet. Introduce capacitive touchscreens and “Bring Your Own Device” (BYOD) streaming options to quickly elevate the lowest-rated passenger touchpoint while simultaneously reducing long-term maintenance costs.
* **“Gold Standard” Cabin Refurbishment:** Improve the low Value for Money score (2.8/5.0) by benchmarking seat ergonomics against the high-performing Boeing 747-400 (4.7 rating). Integrate slimline seatbacks and four-way adjustable headrests to enhance perceived legroom and comfort without reducing seat density.
* **Route-Specific Operational Audits:** Leverage the Tableau “Heat Map” to pinpoint regions with consistently lower satisfaction levels. Instead of implementing fleet-wide adjustments, introduce targeted solutions—such as regionally customized catering to address the 2.4/5.0 Food rating, or focused ground-staff training at hubs exhibiting service gaps.
* **Dynamic Performance Monitoring:** Establish an automated system where any route that falls below a 3.0 average rating for two consecutive weeks automatically triggers a structured service review. This ensures data-driven responsiveness while safeguarding British Airways’ premium brand standards.

## Tools & Technologies Used
* **Data Visualization:** Tableau
* **Data Source:** British Airways Customer Review Data
