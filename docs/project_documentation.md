

<h1 align="center">🔌 EV Market Analysis in India</h1>

<div style="display: flex; justify-content: space-between; padding: 10px; background-color: #f4f4f4; border-radius: 8px;">
    <h4>📅 Date: April 2025</h4>
    <h4>🛠️ Tools Used: Python, Pandas, Seaborn</h4>
    <h4>🏷️ Domain: Automotive</h4>
</div>


---

### 🌍 **Backgroound**  
The global shift toward sustainable transportation has fueled rapid growth in the **electric vehicle (EV) market**. Countries like the US have seen significant adoption, with companies like **AtliQ Motors** capturing a strong foothold, **25% market share** in the EV/hybrid segment in North America.

 
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

#### `1. List the top 3 and bottom 3 makers for the fiscal years 2023 and 2024 in terms of the number of 2-wheelers sold.`

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

#### `2. Identify the top 5 states with the highest penetration rate in 2-wheeler and 4-wheeler EV sales in FY 2024.`

> **2-Wheeler Segment:**
<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/2Q1_Top5_States_with_the_highest_Penetration_Rate_in_2_wheeler.png?raw=true" alt="Bottom3 FY 2023" width="700"/>

  - **Goa** leads with the highest penetration rate at **~18%**, indicating a strong shift toward electric 2-wheelers.
  - **Kerala** and **Karnataka** follow closely with **13.5%** and **11.6%** penetration, respectively.
  - **Maharashtra** and **Delhi** also show solid adoption with rates above **9%**.
  
> **4-Wheeler Segment:**
<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/2Q2_Top5_States_with_the_highest_Penetration_Rate_in_4_wheeler.png?raw=true" alt="Bottom3 FY 2024" width="700"/>

  - **Kerala** again tops the chart at **~5.76%**, showing balanced adoption across both segments.
  - **Chandigarh** and **Delhi** demonstrate relatively high penetration in the 4-wheeler category with over **4%** each.
  - **Karnataka** and **Goa**, while strong in 2-wheelers, also maintain similar penetration in 4-wheelers (~4.25%).

---

#### `3. List the states with negative penetration (decline) in EV sales from 2022 to 2024.`
**Between 2022 and 2024, no states recorded a decline in EV penetration. This indicates a positive and consistent growth trend in EV adoption across all states during this period.**

---

#### `4. What are the quarterly trends based on sales volume for the top 5 EV makers (4-wheelers) from 2022 to 2024?`

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/4Q1_Quarterly_Sales_Trend_for_Top5_EV_Makers_4Wheelers.png?raw=true" alt="Bottom3 FY 2024" width="750"/>

> **How the top 5 four-wheeler EV makers performed over the last three fiscal years:**

- **Tata Motors** showed strong and steady growth in sales every year. It had the highest sales among all, ending with over **17K units in Q4 2024**.

- **Mahindra & Mahindra** had a big jump in early 2024 with **over 10K units in Q1**, but sales dropped in the next quarters.

- **MG Motor** grew well, especially in 2024. It doubled its sales from **Q1 to Q4**.

- **Hyundai Motor** had slow but steady growth. Sales were much lower than others but increasing over time.

- **BYD India** entered the market in 2022. It picked up pace quickly, crossing **400+ units per quarter** by 2024.


---

#### `5. How do the EV sales and penetration rates in Delhi compare to Karnataka for 2024?`

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/5Q1_EV_Sales_and_Penetration_Rate_by_State.png?raw=true" alt="Bottom3 FY 2024" width="500"/>

- **Karnataka** sold **1.6 lakh EVs**, while **Delhi** sold **46.7K EVs** in FY 2024.
- Despite Delhi being a major urban hub, **Karnataka** not only sold more EVs but also had a **higher EV penetration rate** of **10.18%**, compared to **7.71%** for Delhi.


---

#### `6. List down the compounded annual growth rate (CAGR) in  4-wheeler EV units for the top 5 makers from 2022 to 2024.`

The data highlights that while legacy manufacturers like Tata Motors continue to lead in absolute volume, emerging players such as BYD India are expanding their footprint at a much faster rate, underscoring their increasing competitiveness in the 4-wheeler EV market.

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/6Q1_CAGR_of_top_5_4-wheeler_EV_makers_2022_2024.png?raw=true" alt="Bottom3 FY 2024" width="700"/>

- **BYD India** recorded the highest CAGR at **5.67**, indicating rapid expansion and growing market presence in the 4-wheeler EV segment.
- **Hyundai Motor** followed with a CAGR of **2.55**, reflecting consistent year-over-year growth.
- **Mahindra & Mahindra** and **MG Motor** exhibited moderate growth with CAGRs of **1.40** and **1.31**, respectively.
- **Tata Motors**, while maintaining the highest absolute sales volume, reported a relatively lower CAGR of **0.95**, suggesting a more stabilized growth pattern.


---

#### `7. List down the top 10 states that had the highest compounded annual growth rate (CAGR) from 2022 to 2024 in total vehicles sold.`

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/7Q1_CAGR_of_Vehicle_Sales_Top_10_States_2022_2024).png?raw=true" alt="Bottom3 FY 2024" width="750"/>

From 2022 to 2024, **Meghalaya** recorded the highest growth in total vehicle sales with a CAGR of **28.5%**, followed by **Goa (27.4%)** and **Karnataka (25.3%)**.

Other states like **Delhi, Rajasthan, Gujarat, and Assam** also saw strong annual growth rates above **20%**, showing rising vehicle adoption across both urban and smaller states.



---

#### `8. What are the peak and low season months for EV sales based on the data from 2022 to 2024?`

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/8Q1_Monthly_EV_Sales_Heatmap_with_Yearly_&_Monthly_Totals.png?raw=true" alt="Bottom3 FY 2024" width="800"/>

Based on the sales data from 2022 to 2024, **March** stands out as the peak month for EV sales, recording the highest numbers across all three years. Other high-performing months include November, February, and January, indicating strong sales momentum at the beginning and towards the end of the fiscal year.

On the other hand, June consistently shows the lowest sales, followed by July, April, and May. These months reflect a slower phase, likely due to post-fiscal adjustments or seasonal trends.

Understanding these patterns helps in planning campaigns, inventory, and promotions more strategically throughout the year.

---

#### `9. What is the projected number of EV sales (including 2-wheelers and 4-wheelers) for the top 10 states by penetration rate in 2030, based on the compounded annual growth rate (CAGR) from previous years?`

> Using the **CAGR** from 2022 to 2024, the projected EV sales for 2030 highlight aggressive growth in several states:

<img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/9Q1_Projected_EV_Sales_in_2030.png?raw=true" alt="Bottom3 FY 2024" width="750"/>

- **Kerala** and **Maharashtra** are projected to surpass **11 million** and **13 million** EV sales respectively by 2030, driven by strong adoption and consistent growth rates.
- **Karnataka** is also expected to cross **8.3 million** sales, maintaining its position as a key EV market.
- **Goa**, despite starting from a smaller base, shows the **highest growth trajectory**, with projected sales of over **2.4 million** EVs due to a CAGR of **1.46**.
- **Chhattisgarh** and **Odisha** also show impressive projections, reaching **7.1 million** and **2.7 million** respectively, reflecting accelerating EV adoption in emerging markets.
- **Chandigarh**, with the **highest CAGR (1.64)**, is projected to approach **1 million** EV sales.
- **Delhi** and **Tamil Nadu**, despite already being strong EV adopters, are expected to reach **1–1.5 million** in projected sales, indicating steady yet moderate growth compared to others.

 These projections underline a **nationwide shift towards electric mobility**, with both major and smaller states poised for substantial growth by 2030.


---

#### `10. Estimate the revenue growth rate of 4-wheeler and 2-wheelers EVs in India for 2022 vs 2024 and 2023 vs 2024, assuming an average unit price.`

| Vehicle Category | Average Price (INR) |
|-----------------|------------------|
| **2-Wheeler**   | 85,000           |
| **4-Wheeler**   | 1,500,000        |


<table>
  <tr>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/10Q1_EV_Revenue_Trends_by_Vehicle_Category_2022_2024.png?raw=true" alt="Revenue Growth of EVs" width="500"/>
    </td>
    <td>
      <img src="https://github.com/Chakradhar-M/EV-Market-Analysis/blob/main/resources/plots/10Q2_EV_Revenue_Growth_Rates_by_Vehicle_Category_2022_2024.png?raw=true" alt="Revenue Growth Rate of EVs" width="550"/>
    </td>
  </tr>
</table>


- **4-Wheelers** revenue jumped from ₹2,786 Cr in 2022 to ₹13,035 Cr in 2024, a **368% growth**, with a strong **₹5,931 Cr** increase just from 2023 to 2024 (**+83%**).

- **2-Wheelers** revenue grew from ₹2,147 Cr in 2022 to ₹7,928 Cr in 2024, a **269% rise**, adding **₹1,741 Cr** over the past year (**+28%**).

 **While both segments are expanding, **4-wheelers are driving higher revenue growth**, indicating rising demand for premium EVs.**

---


