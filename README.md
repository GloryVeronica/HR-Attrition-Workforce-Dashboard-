**HR-Attrition-Workforce-Dashboard**

---

TalentView is a Power BI HR analytics project that analyzes workforce headcount, attrition trends, separation reasons, and hiring insights. It uses a structured data model, DAX measures, and interactive dashboards to help HR teams understand employee turnover and workforce composition.

---

**TalentView – HR Attrition & Workforce Analytics Dashboard**


**Project Overview**
**TalentView** is a comprehensive **HR analytics dashboard built in Power BI** to analyze workforce size, employee movement, attrition drivers, and hiring performance. The dashboard transforms raw HR data into meaningful insights that help HR teams understand workforce health, identify retention risks, and evaluate recruitment effectiveness.

---

**Dashboard Structure**
The project consists of **five analytical pages**, each designed for a specific HR use case:

1. **KPI Summary**
2. **Workforce Overview**
3. **Attrition Analysis**
4. **Hiring Analysis**
5. **My Analysis (Advanced HR Insights)**

---

 **KPI Summary Dashboard**

**Purpose**
Provides a **high-level snapshot** of overall workforce health and employee movement.

**Key KPIs Displayed**
- **Total Headcount:** **30K**  
- **Active Headcount:** **27K**  
- **New Hires:** **371**  
- **Total Separations:** **300**  
- **Attrition Rate %:** **30%**  
- **Attrition Rate % (Rolling 12 Months):** **0.30**  
- **Average Tenure:** **6.46 years**  
- **Employees Interviewed:** **742**  
- **Employees Resigned:** **63**  
- **Employees Terminated:** **75**  
- **Net Workforce Change:** **+296**

**Key Insight**
Despite noticeable attrition, **strong hiring activity results in overall workforce growth**, indicating effective recruitment efforts.

---

**Workforce Overview Dashboard**

**Purpose**
Focuses on **workforce composition, diversity, and distribution**.

**Visuals Explained**

**Headcount by Department**
Shows employee distribution across **Engineering, Finance, HR, Operations, and Sales**, helping identify departments with the highest workforce concentration.

**Employee Distribution by Gender**
Displays workforce split by **Male, Female, and Other**, supporting diversity and inclusion analysis.

**Employee Distribution by Age Group**
Breaks down employees across **18–25, 26–35, 36–45, 46–55, and 55+**, enabling workforce aging and succession planning.

**Employee Distribution by Ethnicity**
Shows ethnic representation across the organization, supporting diversity monitoring.

**Key Insight**
Engineering and Finance have the highest headcount, while demographic distribution reflects a **balanced and diverse workforce**.

---

**Attrition Analysis Dashboard**

**Purpose**
Explains **why employees are leaving**, when attrition occurs, and whether exits are voluntary or involuntary.

**Visuals Explained**

**Attrition Rate by Month**
Displays monthly attrition trends to identify **seasonal patterns and spikes**.

**Voluntary vs Involuntary Attrition**
Compares **employee-driven exits** versus **organization-driven exits**.

**Separations by Reason**
Breaks down exits by **Resignation, Termination, Retirement, and Contract End**, identifying major attrition drivers.

**Key Influencers (AI Visual)**
Uses Power BI AI to highlight factors influencing attrition such as **Department, Manager, and Demographics**.

**Key Insight**
Attrition is influenced by both voluntary and involuntary factors, with **department- and manager-level trends indicating retention risk areas**.

---

**Hiring Analysis Dashboard**

**Purpose**
Evaluates **recruitment efficiency and hiring pipeline performance**.

**Visuals Explained**

**Hiring Funnel**
Shows recruitment stages **Applied → Screened → Interviewed → Hired**, highlighting candidate drop-offs.

**Employees Hired by Month**
Tracks monthly hiring trends to assess recruitment consistency.

**Time-to-Hire by Department**
Measures average hiring duration by department, identifying bottlenecks.

**Key Insight**
The recruitment funnel shows **significant drop-offs between stages**, and time-to-hire varies across departments, indicating optimization opportunities.

---

**My Analysis (Advanced HR Insights)**

**Purpose**
Provides **deep-dive insights** combining hiring, attrition, and job-role analysis.

**Visuals Explained**

**Voluntary vs Involuntary Exits by Department**
Highlights departments with higher voluntary or involuntary exits.

**Funnel Value by Department and Stage**
Compares hiring efficiency across departments.

**Employees Hired, Resigned, and Terminated by Job Role**
Shows employee movement at the job-role level.

**Key Insight**
Certain departments and job roles experience higher employee movement, helping HR **prioritize retention and workforce planning strategies**.

---

**Security & Deployment**
- **Row-Level Security (RLS)** implemented for managers and HR users  
- Published to **Power BI Service**  
- Shared as a **Power BI App** with view-only access  

---

**Tools & Technologies Used**
- **Power BI Desktop**
- **Power BI Service**
- **Microsoft Excel**
- **GitHub**

---

**Conclusion**
The **TalentView HR Analytics Dashboard** delivers a complete workforce intelligence solution by combining headcount, attrition, and hiring data into interactive dashboards. It enables HR teams to **monitor workforce health, identify attrition risks, and make data-driven decisions**.
