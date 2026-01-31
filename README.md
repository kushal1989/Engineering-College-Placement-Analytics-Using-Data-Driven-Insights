# Engineering College & Placement Analytics Using Data-Driven Insights

## Project Overview
Choosing the right engineering college is a critical decision for students and parents.  
With thousands of colleges offering varied fee structures, placement packages, ratings, and locations, it becomes difficult to identify **value-for-money institutions**.

This project uses **Exploratory Data Analysis (EDA)** and **statistical hypothesis testing** to analyze engineering college data and answer real-world questions related to **fees, placements, ROI, and ratings**.

---

## Business Problem
Students often face confusion due to:
- Wide variation in tuition fees
- Inconsistent placement outcomes
- Ratings and rankings that may not reflect real value
- Lack of data-driven comparison tools

### Key Questions Addressed:
- Is paying higher fees really worth it?
- Do top-rated colleges always provide better placements?
- Which states offer better ROI colleges?
- Are there affordable colleges with strong placement records?

---

## Project Objectives
- Analyze the relationship between **tuition fees and placement packages**
- Identify colleges offering **high Return on Investment (ROI)**
- Compare college performance **across locations**
- Evaluate whether **ratings influence placements**
- Support EDA findings with **statistical hypothesis testing**

---

## Dataset Description
Data was scraped from the following website:

🔗 https://www.collegesearch.in/engineering-colleges-india

### Key Columns:
| Column Name | Description |
|------------|-------------|
| college_name | Name of the engineering college |
| rating | Student rating (out of 5) |
| location | College location (State/City) |
| courses_offered | Engineering programs available |
| tution_fee | Tuition fee (INR) |
| exams_accepted | Entrance exams accepted |
| highest_package | Highest placement package (LPA) |

---

## Data Cleaning & Preprocessing
- Removed duplicates
- Handled missing values (`Get Fee Details`, `-`)
- Converted monetary values to numeric format
- Removed invalid and inconsistent records
- Ensured uniform data types
- Filtered extreme values carefully (only if invalid)

---

## Exploratory Data Analysis (EDA)

### Univariate Analysis
- Tuition fee distribution
- Placement package distribution
- Rating distribution
- Location frequency analysis

### Bivariate Analysis
- Tuition Fee vs Highest Package
- Rating vs Tuition Fee
- Rating vs Placement Package

### Multivariate Analysis
- Correlation heatmap across numeric variables

---

## Hypothesis Testing
Statistical tests were performed to validate EDA observations.

### Tests Used:
- **One-way ANOVA**

## Key Insights
- Tuition fees are **right-skewed**; most colleges are mid-fee
- High fees do **not guarantee** better placements
- Ratings show **weak correlation** with placements
- Several **mid-fee colleges offer strong ROI**
- Some states consistently provide better value-for-money colleges

---

## Final Conclusion
- Paying very high fees is **not always worth it**
- ROI-based comparison is more reliable than rankings alone
- Students should focus on **fees vs realistic placement outcomes**
- Data-driven decisions reduce risk and improve outcomes

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (ANOVA)
- Jupyter Notebook

 Run the Jupyter Notebook step-by-step

```bash
pip install pandas numpy matplotlib seaborn scipy
