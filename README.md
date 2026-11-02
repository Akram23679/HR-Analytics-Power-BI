# HR Analytics: Workforce & Attrition Insights

**Project PRDA-03 · Akram Ali · October 2026**

An HR analytics case study that explores workforce composition, hiring patterns, employee attrition and retention opportunities across **22,214 employee records**. The analysis turns raw people data into practical recommendations for HR teams.

This repository contains a responsive portfolio webpage that presents the project, its interactive charts, key findings and recommendations.

---

## Live Demo

> Add your GitHub Pages link here once deployed, for example:
> `(https://akram23679.github.io/HR-Analytics-Power-BI/)`

---

## Project Overview

| Item | Detail |
|---|---|
| Employee records | 22,214 |
| Data attributes | 13 |
| Departments | 13 |
| States represented | 7 |
| Overall attrition rate | 13.1% |
| Recorded leavers | 2,901 |
| Analysis cut-off date | 29 September 2026 |

### Analysis themes
- **Workforce composition:** age, gender, race, department and location
- **Hiring patterns:** annual hiring trends and workforce distribution
- **Attrition:** exits by year, department, tenure and work arrangement
- **Retention opportunities:** early-tenure risk, succession planning and flexible work

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL Workbench | Database access |
| Microsoft Excel | Data review and preparation |
| Power BI Desktop | Two-page workforce and attrition dashboard |
| Tableau | Parallel dashboard and calculated fields |
| DAX | Employee status, age, tenure and date attributes |
| HTML / CSS / JavaScript | Portfolio webpage |
| Chart.js | Interactive charts on the webpage |

---

## Data Preparation

- Loaded and reviewed 22,214 employee records
- Checked employee IDs for duplicates
- Converted hire and birth dates using day-month-year locale
- Treated blank termination dates as active employees
- Treated future-dated termination dates as active at the project cut-off
- Created **Employee Status, Age Group, Hire Year, Term Year, Tenure** and **Tenure Group** fields in DAX

---

## Key Findings

1. **Consistent hiring** – roughly 1,100 hires per year from 2001 to 2020, with no major freeze or sudden expansion.
2. **Ohio concentration** – 81% of employees (18,025) are based in Ohio, with 16,871 in Cleveland.
3. **Near-balanced gender mix** – 50.8% male, 46.5% female, 2.7% non-conforming.
4. **Early-tenure risk** – 39% of leavers (1,143 of 2,901) left within their first five years.
5. **Department hotspots** – Auditing has the highest attrition rate (19.2%) but only 52 employees; Legal (16.7%) is the larger-team warning sign.
6. **Remote vs headquarters** – remote employees show lower attrition (12.3%) than headquarters employees (13.3%). This is an association, not proof of cause.

---

## Recommendations

1. Strengthen early-career retention with onboarding, mentoring and regular check-ins
2. Investigate attrition in Legal and Auditing through exit interviews and surveys
3. Plan hiring against attrition by tracking quarterly net headcount
4. Continue evaluating remote and hybrid work as a retention lever
5. Prepare succession plans, since about one-fifth of the workforce is aged 50+
6. Reduce location concentration by growing branch offices or remote hiring
7. Keep monitoring gender and race representation and attrition across groups
8. Improve HR data quality (future-dated terminations, recent hires, automatic age calculation)

---

## Repository Structure

```
├── index.html    # Portfolio page: content, charts and interactivity
├── styles.css    # All page styling, light/dark themes and responsive layout
└── README.md     # Project documentation
```

---

## Run Locally

No build step is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `index.html` in any modern browser.

An internet connection is needed to load Google Fonts and Chart.js from their CDNs.

## Deploy with GitHub Pages

1. Push the files to your repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder.
4. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## Webpage Features

- Responsive layout for desktop, tablet and mobile
- Light / dark theme toggle (choice remembered in the browser)
- Tabbed summary card (Workforce, Attrition, Location)
- Nine interactive Chart.js charts with tooltips
- Sections for brief, data & method, dashboard, findings, recommendations and limitations

---

## Limitations

- The dataset is a snapshot and does not explain *why* employees leave.
- Future-dated terminations were treated as active at the 29 September 2026 cut-off.
- Some department rates are based on small populations and should be read alongside headcounts.
- Demographic and location comparisons show patterns, not causation.

---

## Author

**Akram Ali**  
Data Analytics Project · PRDA-03

Feel free to connect or open an issue with questions or feedback.
