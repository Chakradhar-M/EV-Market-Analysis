

<h1 align="center">🔌 EV Market Analysis in India</h1>

<div style="display: flex; justify-content: space-between; padding: 10px; background-color: #f4f4f4; border-radius: 8px;">
    <h4>📅 Date: April 2025</h4>
    <h4>🛠️ Tools Used: Python, Pandas, Seaborn</h4>
    <h4>🏷️ Domain: Automotive</h4>
</div>


---

### 🌍 **Backgroound**  
The global shift toward sustainable transportation has fueled rapid growth in the **electric vehicle (EV) market**. Countries like the US have seen significant adoption, with companies like **AtliQ Motors** capturing a strong foothold, **25% market share** in the EV/hybrid segment in North America.

In contrast, **India’s EV adoption is still in its early stages**, presenting both challenges and opportunities for new entrants.
 
As part of its international expansion, **AtliQ Motors** is exploring a launch of its bestselling EV models in India, where its market share currently stands at less than 2%. To make an informed decision, **Bruce Haryali**, Chief of AtliQ Motors India, has requested a detailed market analysis to understand the EV landscape in the country.

As the data analyst on the team, my task is to analyze available data, draw insights, and support strategic recommendations for AtliQ's entry into the Indian market.

---

### 🎯 **Objectives**  
The goal of this analysis is to study the current EV and hybrid vehicle market in India and extract meaningful insights that can guide AtliQ Motors in making informed decisions for its market entry strategy.

Specifically, the objectives are to:

- Understand the current state of EV and hybrid vehicle adoption in India.  
- Identify top-performing regions, vehicle categories, and manufacturers.  
- Analyze growth trends and registration patterns over recent years.  
- Explore market opportunities and possible challenges for new entrants. 

---

###  📂 Essential Project Links  

| 🧭 Resource | 🔗 Access |
|------------|----------|
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/database.png?raw=true" width="20" style="vertical-align:middle;"> **Data Source** | 👉 [Click to View Data Source](https://codebasics.io/challenge/codebasics-resume-project-challenge/15) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/kaggle.png?raw=true?raw=true" width="22" style="vertical-align:middle;"> **Kaggle Notebook** | 📊 [View Kaggle Notebook](#) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/youtube.png?raw=true" width="20" style="vertical-align:middle;"> **Project Presentation** | 🎬 [Watch Presentation](#) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/linkedin.png?raw=true" width="22" style="vertical-align:middle;"> **LinkedIn Post** | 🔗 [Read on LinkedIn](#) |

📌 **Tip:** Right-click or Ctrl + Click to open links in a new tab.

---

### **📊 Sample Raw Data**

#### **`electric_vehicle_sales_by_makers data`**
<div style="overflow-x:auto; white-space:nowrap;">

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Vehicle&nbsp;Category</th>
      <th>Maker</th>
      <th>Electric&nbsp;Vehicles&nbsp;Sold</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01-Sep-23</td>
      <td>4-Wheelers</td>
      <td>Tata&nbsp;Motors</td>
      <td>3126</td>
    </tr>
    <tr>
      <td>01-Sep-23</td>
      <td>4-Wheelers</td>
      <td>MG&nbsp;Motor</td>
      <td>676</td>
    </tr>
    <tr>
      <td>01-Sep-23</td>
      <td>4-Wheelers</td>
      <td>Mahindra&nbsp;&amp;&nbsp;Mahindra</td>
      <td>1668</td>
    </tr>
  </tbody>
</table>
</div>




####  **`electric_vehicle_sales_by_state data`**

<div style="overflow-x:auto; white-space:nowrap;">

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>State</th>
      <th>Vehicle&nbsp;Category</th>
      <th>Electric&nbsp;Vehicles&nbsp;Sold</th>
      <th>Total&nbsp;Vehicles&nbsp;Sold</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01-Mar-24</td>
      <td>Maharashtra</td>
      <td>2-Wheelers</td>
      <td>26668</td>
      <td>152563</td>
    </tr>
    <tr>
      <td>01-Mar-24</td>
      <td>Karnataka</td>
      <td>2-Wheelers</td>
      <td>22742</td>
      <td>123800</td>
    </tr>
    <tr>
      <td>01-May-23</td>
      <td>Maharashtra</td>
      <td>2-Wheelers</td>
      <td>20585</td>
      <td>126680</td>
    </tr>
  </tbody>
</table>
</div>



#### **`dim_date data`**

<div style="overflow-x:auto; white-space:nowrap;">

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Fiscal&nbsp;Year</th>
      <th>Quarter</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01-Apr-21</td>
      <td>2022</td>
      <td>Q1</td>
    </tr>
    <tr>
      <td>01-May-21</td>
      <td>2022</td>
      <td>Q1</td>
    </tr>
    <tr>
      <td>01-Jun-21</td>
      <td>2022</td>
      <td>Q1</td>
    </tr>
  </tbody>
</table>
</div>

---

### Analysis & Insights 

#### 1. List the top 3 and bottom 3 makers for the fiscal years 2023 and 2024 in terms of the number of 2-wheelers sold.

<table>
  <tr>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/1Q1_Top3_EV_Makers_In_FY_2023.png?raw=true" alt="Top3 FY 2023" width="500"/>
    </td>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/1Q2_Top3_EV_Makers_In_FY_2024.png?raw=true" alt="Top3 FY 2024" width="500"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/1Q3_Bottom3_EV_Makers_In_FY_2023.png?raw=true" alt="Bottom3 FY 2023" width="500"/>
    </td>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/1Q4_Bottom3_EV_Makers_In_FY_2024.png?raw=true" alt="Bottom3 FY 2024" width="500"/>
    </td>
  </tr>
</table>


- **OLA Electric** dominated the EV 2-wheeler market in both fiscal years.  
  - In FY 2023, it led with **152,583** units sold.
  - In FY 2024, it nearly **doubled** its sales, reaching **322,489** units.

- **TVS** emerged as a strong contender in FY 2024 with **180,743** units, marking a significant jump in EV sales performance.

- **Ather** also showed strong growth, making it to the top 3 in FY 2024 with **107,552** units.

- Makers like **Jitendra**, **Being**, and **Pure EV** recorded the **lowest sales in FY 2023**, each selling fewer than **12,000 units**.

- In FY 2024, **BattRE Electric**, **Revolt**, and **Kinetic Green** were the lowest performers, all selling **under 10,000 units**.

---


#### 2. Identify the top 5 states with the highest penetration rate in 2-wheeler and 4-wheeler EV sales in FY 2024.

#### 3. List the states with negative penetration (decline) in EV sales from 2022 to 2024.

#### 4. What are the quarterly trends based on sales volume for the top 5 EV makers (4-wheelers) from 2022 to 2024?

#### 5. How do the EV sales and penetration rates in Delhi compare to Karnataka for 2024?

#### 6. List down the compounded annual growth rate (CAGR) in 4-wheeler units for the top 5 makers from 2022 to 2024.

#### 7. List down the top 10 states that had the highest compounded annual growth rate (CAGR) from 2022 to 2024 in total vehicles sold.

#### 8. What are the peak and low season months for EV sales based on the data from 2022 to 2024?

#### 9. What is the projected number of EV sales (including 2-wheelers and 4-wheelers) for the top 10 states by penetration rate in 2030, based on the compounded annual growth rate (CAGR) from previous years?

#### 10. Estimate the revenue growth rate of 4-wheeler and 2-wheelers EVs in India for 2022 vs 2024 and 2023 vs 2024, assuming an average unit price.

---
