# Top 20 Data Analyst Projects to Get Hired

> 20 portfolio projects, ordered from beginner to advanced, with the tools to use, a dataset for each, and what recruiters look for.

**Curated by [Aditya Kalyan](https://www.linkedin.com/in/your-profile) | Data Analytics Mentor**

![Projects](https://img.shields.io/badge/projects-20-2563EB)
![Level](https://img.shields.io/badge/level-beginner%20to%20advanced-F59E0B)
![Tools](https://img.shields.io/badge/tools-Excel%20%7C%20SQL%20%7C%20Power%20BI%20%7C%20Tableau%20%7C%20Python-22C55E)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen)

---

## Why This Repo?

Recruiters skim hundreds of resumes. A certificate shows you finished a course. A project shows you can **turn data into decisions**. This repo gives you 20 project ideas that cover the skills hiring managers ask for most:

- Data cleaning and Excel dashboards
- SQL analysis and window functions
- Power BI and Tableau dashboards
- Python (Pandas, EDA, visualization)
- Business case studies (sales, HR, marketing, finance, healthcare, e-commerce, supply chain)
- Advanced analytics (funnel, RFM segmentation, cohort retention, A/B testing, forecasting, churn)

---

## Table of Contents

- [Project List](#project-list)
- [How to Use This Repo](#how-to-use-this-repo)
- [Suggested Folder Structure](#suggested-folder-structure)
- [Project README Template](#project-readme-template)
- [How to Showcase Your Projects](#how-to-showcase-your-projects)
- [Pro Tip: Tell a Business Story](#pro-tip-tell-a-business-story)
- [Contributing](#contributing)
- [Connect](#connect)

---

## Project List

### Beginner

| # | Project | Tools | Dataset | What recruiters see |
|---|---|---|---|---|
| 01 | Sales Dashboard in Excel | Excel | [Superstore Sales](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) | You turn numbers into decisions |
| 02 | Clean Messy Data Like a Pro | Excel, Power Query | [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) | Attention to detail, real-world readiness |
| 03 | SQL Retail Sales Analysis | SQL | [Superstore Sales](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) | You can query real databases |
| 04 | HR Attrition Dashboard | Power BI | [IBM HR Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) | People analytics skills |
| 05 | Python EDA on Real Data | Pandas, Matplotlib | [Titanic](https://www.kaggle.com/c/titanic) | You think like an analyst |
| 06 | Marketing Campaign ROI Analysis | Excel, SQL | [Bank Marketing (UCI)](https://archive.ics.uci.edu/dataset/222/bank+marketing) | You link analysis to revenue |

### Intermediate

| # | Project | Tools | Dataset | What recruiters see |
|---|---|---|---|---|
| 07 | E-commerce Dashboard in Tableau | Tableau | [Olist E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) | Polished, interactive storytelling |
| 08 | Finance Dashboard in Power BI | Power BI, DAX | Microsoft "Financial Sample" (Power BI Desktop: Get Data > Samples) | Reports stakeholders trust |
| 09 | Rank Customers with SQL Window Functions | SQL | [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) | Interview-level SQL skill |
| 10 | Healthcare Readmission Analysis | Python, Tableau | [Diabetes 130-US Hospitals](https://archive.ics.uci.edu/dataset/296/diabetes-130-us-hospitals-for-years-1999-2008) | You handle sensitive, high-impact data |
| 11 | Data Storytelling with Python | Seaborn, Plotly | [Gapminder](https://www.gapminder.org/data/) | Communication skills |
| 12 | Supply Chain and Inventory Dashboard | Power BI, SQL | [DataCo Supply Chain](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) | Operations thinking |
| 13 | Funnel Analysis with SQL | SQL | [eCommerce Behavior (REES46)](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) | You find where businesses lose money |
| 14 | Customer Segmentation with RFM | Python, Pandas | [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) | Analysis that drives targeted campaigns |

### Advanced

| # | Project | Tools | Dataset | What recruiters see |
|---|---|---|---|---|
| 15 | Cohort Retention Analysis | SQL, Python | [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) | Product analytics depth |
| 16 | A/B Test Analysis | Python, SciPy | [Marketing A/B Testing](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing) | Statistical thinking, not guesswork |
| 17 | Sales Forecasting for Next Quarter | Python, statsmodels | [Superstore Sales](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) | You help businesses plan ahead |
| 18 | Predict Customer Churn | Python, scikit-learn | [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) | Predictive, business-focused thinking |
| 19 | Automated Reporting Pipeline | SQL, Python, Power BI | [Olist E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) | Efficiency and real workflow skills |
| 20 | End-to-End Capstone Case Study | SQL, Python, Power BI | [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) or [DataCo](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) | The full analyst workflow |

**Notes**
- Kaggle datasets need a free Kaggle account to download. UCI datasets download without one.
- Some datasets repeat across projects. Reusing one is fine to start, but a stronger portfolio uses a different dataset for each project.
- Dataset pages can move or change. If a link is broken, search the dataset name on [Kaggle](https://www.kaggle.com/datasets), [UCI](https://archive.ics.uci.edu/), or [Google Dataset Search](https://datasetsearch.research.google.com/).

---

## How to Use This Repo

1. **Fork or clone** this repo.
2. **Pick one project** that matches your level. Start with a beginner project if you are new.
3. **Download the dataset** from the link in the table.
4. **Build it** in the listed tools.
5. **Document it** using the README template below.
6. **Publish it** to GitHub and share one insight on LinkedIn.

```bash
git clone https://github.com/<your-username>/top-20-data-analyst-projects.git
cd top-20-data-analyst-projects
```

---

## Suggested Folder Structure

```
top-20-data-analyst-projects/
├── README.md
├── 01-excel-sales-dashboard/
│   ├── README.md
│   ├── data/
│   ├── dashboard/
│   └── images/
├── 02-data-cleaning/
├── 03-sql-retail-analysis/
│   ├── queries.sql
│   └── README.md
├── ...
├── 18-customer-churn/
│   ├── notebook.ipynb
│   └── README.md
├── 20-capstone/
└── resources/
```

> Do not commit very large datasets. Add a `data/README.md` with the download link and instructions instead.

---

## Project README Template

Copy this into each project folder:

```markdown
# Project Title

## Business Problem
What question are you answering, and who needs the answer?

## Dataset
Source link, number of rows and columns, time period.

## Tools Used
Excel / SQL / Power BI / Tableau / Python (libraries)

## Approach
1. Data cleaning steps
2. Analysis steps
3. Visualization steps

## Key Insights
- Insight 1 (with a number)
- Insight 2 (with a number)
- Insight 3 (with a number)

## Recommendations
What should the business do next?

## Screenshots
Dashboard images or chart previews.

## How to Run
Steps to reproduce.
```

---

## How to Showcase Your Projects

| Where | What to do |
|---|---|
| **GitHub** | Clean code, clear README, screenshots, and a `requirements.txt` for Python projects |
| **Portfolio site** | One page per project: problem, process, result |
| **LinkedIn** | Post one insight per project, add a dashboard image, tag the dataset source |
| **Resume** | List your 3 best projects with tools and a measurable result |

---

## Pro Tip: Tell a Business Story

Do not just show a dashboard. Walk through this flow:

1. **Problem:** What was the question?
2. **Data:** What did you use?
3. **Insight:** What did you find?
4. **Action:** What should change?
5. **Impact:** What is the likely result?

Recruiters hire analysts who explain the "so what."

---

## Contributing

Contributions are welcome.

1. Fork the repo
2. Create a branch: `git checkout -b add-project-idea`
3. Commit your changes: `git commit -m "Add new dataset link"`
4. Push and open a Pull Request

Good contributions: working dataset links, solution examples, improved templates, and new project ideas.

---

## License

Project ideas and documentation are released under the [MIT License](LICENSE). Datasets belong to their original owners. Check each dataset's license before using or redistributing it.

---

## Connect

**Aditya Kalyan** | Data Analytics Mentor

- LinkedIn: [your-profile](https://www.linkedin.com/in/your-profile)
- Instagram: [@your-handle](https://www.instagram.com/your-handle)

If this repo helped you, give it a star and share it with a friend who is job hunting.
