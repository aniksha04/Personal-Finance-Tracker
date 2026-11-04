# Personal Finance Tracker & Power BI Dashboard

Analysis of **[X] transactions over [13] months** of my UPI history (PhonePe statement) using Python, Pandas, Matplotlib and Power BI, to understand where my money goes and when spending exceeds income.

## Problem
Raw UPI statements are hard to read: junk rows, text dates and amounts, and no categories. I wanted to turn mine into clear monthly insights about spending and cash flow.

## What I Did
- Cleaned the raw statement (removed junk rows, converted text dates and amounts to proper types)
- Categorised transactions into **[X] categories** using keyword rules
- Compared money in vs. money out for each month
- Identified the months where spending exceeded money in
- Built an interactive Power BI dashboard with KPI cards, a transaction-type slicer, and category and monthly charts

## Key Findings
- Spending exceeded money in during **4 of [13] months**
- Education fee payments caused **3 of those 4 months**
- Top spending categories: **[Category 1] ([X]%)**, **[Category 2] ([X]%)**
- Total money in: **₹[X]** | Total money out: **₹[X]** | Net cash flow: **₹[X]**

## Recommendation
Set aside a fixed amount each month for large, irregular payments such as fees, so they don't push spending above income.

## Dashboard


![Dashboard Overview](images/dashboard1.png)




![Monthly Trends](images/dashboard2.png)



## Tech Stack
- **Python:** Pandas, Matplotlib
- **Power BI:** KPI cards, slicers, category and monthly charts
- **Tools:** Jupyter Notebook, VS Code, Git/GitHub

## Project Files
| File | Description |
|------|-------------|
| `Finance_tracker_public.ipynb` | Data cleaning, categorisation and analysis |
| `Finance-Report-Dashboard.pbix` | Power BI dashboard (open in Power BI Desktop) |
| `images/` | Dashboard screenshots |

## How to Run
1. Clone the repo: `git clone https://github.com/Aniksha04/Personal-Finance-Tracker.git`
2. Install the libraries: `pip install pandas matplotlib jupyter`
3. Open `Finance_tracker_public.ipynb` and run all cells
4. Open the `.pbix` file in Power BI Desktop to explore the dashboard

## Notes
The original data is private and not included. Names in the code are placeholders.

## Author
**Aniksha Shinde** | [GitHub](https://github.com/Aniksha04) | [LinkedIn](https://linkedin.com/in/aniksha-shinde-87987843b)
