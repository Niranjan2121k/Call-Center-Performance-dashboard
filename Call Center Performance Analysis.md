# Call Center Performance Analysis

## Project Overview
This project involves analyzing call center data to extract insights into customer interactions, purchase amounts, call durations, and representative performance. The data has been processed and visualized using Excel and Tableau to provide meaningful insights.

---

## Data Overview
The dataset contains information on:
- Total number of calls
- Purchase amounts
- Call durations
- Customer ratings
- Gender distribution of callers
- Call trends by month, day, and representative

---

## Key Metrics
| Metric | Total | Sample Data |
|--------|--------|-------------|
| Calls | 1,000 | 189 |
| Purchase Amount | 96,623 | 18,415 |
| Call Duration | 89,850 | 16,834 |
| Average Rating | 3.96 | 4.04 |
| Happy Callers | 307 | - |

---

## Data Breakdown
### 1. **Call Distribution by Month**
- Peak call volume observed in **April (29 calls)**.
- The lowest call volume in **December (6 calls)**.
- Calls were distributed consistently across other months, averaging around 16-24 calls.

### 2. **Call Volume by Day of the Week**
| Day | Call Count |
|------|------------|
| Sunday | 36 |
| Monday | 30 |
| Tuesday | 13 |
| Wednesday | 23 |
| Thursday | 23 |
| Friday | 24 |
| Saturday | 40 |

- **Saturday had the highest number of calls (40)**, while **Tuesday had the lowest (13)**.

### 3. **Call Distribution by Gender**
| City | Female | Male | Total |
|------|--------|------|-------|
| Cincinnati | 30 | 26 | 56 |
| Cleveland | 57 | 13 | 70 |
| Columbus | 29 | 34 | 63 |
| **Total** | **116** | **73** | **189** |

- More calls were made by **female customers (116 calls)** compared to **male customers (73 calls)**.

### 4. **Performance of Representatives**
| Representative | Call Count | Purchase Amount ($) |
|---------------|------------|---------------------|
| R01 | 189 | 18,415 |
| R02 | 218 | 20,581 |
| R03 | 207 | 20,872 |
| R04 | 186 | 16,651 |
| R05 | 200 | 20,104 |

- **R03 handled the highest purchase amount ($20,872)** despite having fewer calls than R02.
- **R04 handled the least purchase amount ($16,651)**.

### 5. **Call Distribution by Customer Region**
| City | Customer Code | R01 | R02 | R03 | R04 | R05 | Total |
|------|--------------|-----|-----|-----|-----|-----|-------|
| Cincinnati | C0003 | 891 | 1,332 | 1,282 | 739 | 560 | 4,804 |
| Cleveland | C0008 | 900 | 1,016 | 960 | 940 | 1,193 | 5,009 |
| Columbus | C0005 | 1,104 | 2,280 | 1,445 | 1,722 | 1,196 | 7,747 |

- Columbus had the highest purchase amount with **$7,747**.
- Cleveland's customer **C0008** had significant purchase values spread across all representatives.

---

## **Visual Insights**
### 1. **Call Trends**
- Monthly trends show fluctuating call volumes, with peaks in **April and October**.
- A decrease in call volume is noticeable during **summer months**.

### 2. **Customer Demographics**
- **Cleveland had the most female callers (57)**, while **Cincinnati had a more balanced distribution**.

### 3. **Representative Performance**
- While **R03 had fewer calls than R02**, they had the **highest purchase amount**.
- **R04 had the lowest purchase amount** despite a comparable call count.

---

## **Conclusion**
- The **highest call volumes occur in April and weekends**, indicating peak customer engagement during these times.
- **Columbus generated the highest revenue**, suggesting a strong customer base in that region.
- **Female callers dominated across all cities**, an insight that could influence marketing strategies.
- **R03 demonstrated high efficiency** in closing high-value purchases despite handling fewer calls.

### **Future Recommendations**
- Optimize **weekend staffing** to handle higher call volumes effectively.
- Investigate why **R04 has a lower revenue per call** despite similar call numbers.
- Focus on **Columbus for targeted marketing campaigns**, as it has the highest revenue potential.

---

## **Screenshots**
### **Raw Data (Excel Pivot Tables)**
![Excel Data](Screenshot_2025-03-23_at_4.40.02_PM.png)

### **Tableau Dashboard Visualization**
![Tableau Dashboard](Screenshot_2025-03-23_at_4.49.54_PM.png)

---

## **Project Tools**
- **Data Cleaning & Aggregation**: Microsoft Excel (Pivot Tables)
- **Visualization**: Tableau
- **Database Management**: MySQL (for future integrations)

This analysis provides a comprehensive look into **call center operations**, helping in decision-making for workforce allocation, customer segmentation, and representative performance improvement.

# Final Dashboard
<img width="1405" alt="Screenshot 2025-03-23 at 4 40 02 PM" src="https://github.com/user-attachments/assets/d4ad7e88-a84d-4e57-b9ea-2b2b87affeb3" />




