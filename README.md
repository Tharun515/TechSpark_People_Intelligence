<div align="center">

# TechSpark People Intelligence
### AI-Assisted HR Analytics & Interactive Dashboard

**Turning employee data into clearer workforce, compensation, performance and leave insights.**

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-Explore-6C5CE7?style=for-the-badge)](https://oxidized-tumbleweed-o2w.julius.site/?ref=P7K65GXNPT63&utm_source=shared_artifact)
[![Dataset](https://img.shields.io/badge/Dataset-Synthetic-16A085?style=for-the-badge)](#dataset-overview)
[![Focus](https://img.shields.io/badge/Focus-HR%20Analytics-2980B9?style=for-the-badge)](#dashboard-sections)

</div>

---

## 1. Project Overview

**TechSpark People Intelligence** is an interactive HR analytics project that explores how employee-related data can be transformed into meaningful business information. Using a synthetic employee dataset representing the period **2018–2024**, I developed an AI-assisted dashboard with **Julius AI** to explore workforce composition, compensation patterns, performance ratings and leave trends.

The purpose of this project is to move beyond viewing data as rows and columns in a spreadsheet. Through interactive visualizations, filters and summary metrics, the dashboard makes it easier to examine different workforce dimensions, compare categories and ask more focused analytical questions.

This project combines data understanding, analytical thinking, visualization and practical experimentation with AI. The goal was not simply to generate charts, but to decide what should be explored, guide the AI tool with clear instructions, review its output and refine the dashboard so that the information is easier to understand.

**Live interactive dashboard:** [TechSpark People Intelligence – Julius AI](https://oxidized-tumbleweed-o2w.julius.site/?ref=P7K65GXNPT63&utm_source=shared_artifact)

## 2. Project at a Glance

| Item | Details |
|---|---|
| Project category | HR Analytics / People Analytics |
| Dataset | Synthetic employee master data |
| Dataset period | 2018–2024 |
| Employee records | 210 |
| Dataset attributes | 14 columns |
| Data format | Excel workbook |
| AI-assisted platform | Julius AI |
| Main analysis areas | Workforce, compensation, performance and leave |
| Final output | Interactive dashboard |

## 3. Problem Context & Objective

Employee datasets can contain useful information about workforce composition, salary structures, performance ratings and leave utilization. However, it can be difficult to identify patterns or compare groups by looking at spreadsheet rows alone.

This project explores how an interactive dashboard can make those dimensions easier to investigate. The key objectives were to:

- Understand workforce distribution across departments and locations.
- Explore employee composition using the attributes available in the dataset.
- Analyze salary and bonus patterns across relevant categories.
- Review the distribution of employee performance ratings.
- Explore leave utilization and identify patterns that may deserve further investigation.
- Present the information in an accessible dashboard that supports filtering and exploration.
- Experiment with AI-assisted analysis while keeping human judgment and validation part of the workflow.

## 4. Dashboard Sections

### 4.1 Workforce Overview

This section provides a high-level view of the employee population. It helps explore workforce composition and compare employee distribution across available dimensions such as department, location, grade and other employee attributes.

**Questions explored:**
- How is the workforce distributed across departments?
- Which locations have a larger employee representation?
- How does employee composition vary across available categories?
- What does the overall workforce profile look like?

### 4.2 Compensation Analysis

This section focuses on salary and bonus-related fields. It provides a way to explore compensation distribution and compare patterns across the dimensions available in the dataset.

**Questions explored:**
- How does salary distribution vary across departments or grades?
- How do compensation patterns differ across locations?
- What does the bonus distribution look like?
- Which comparisons may deserve closer review?

### 4.3 Performance & Leave Analysis

This section brings together performance-rating and leave-related information. It helps examine how these measures are distributed and compare them across relevant employee groups.

**Questions explored:**
- How are performance ratings distributed?
- How does leave utilization vary across departments or other categories?
- Are there visible patterns that should be investigated further?
- Which filters help reveal differences between employee groups?

*These are exploratory questions. Patterns in a synthetic dataset are illustrative and do not prove real-world relationships or causation.*

## 5. Interactive Dashboard Experience

The published dashboard is designed for exploration rather than static viewing. Depending on the selected view and available controls, users can:

- Apply filters to focus on selected employee groups or categories.
- Search employee records.
- Compare workforce dimensions.
- Explore visual summaries and underlying data.
- Export filtered information in supported formats, including CSV or PDF.

For the complete interactive experience, visit the live dashboard. Screenshots in this repository can be added as a quick visual reference, but they do not replace the interactive version.

## 6. Dataset Overview

The project uses a synthetic employee master dataset containing **210 records and 14 columns**, representing the period **2018–2024**.

The workbook contains fields relating to employee identity, organizational structure, location, compensation, experience, performance and leave. Examples include:

- Employee ID
- Department and city
- Gender and grade
- Annual salary and bonus percentage
- Experience and employment status
- Reporting manager
- Performance rating
- Leaves taken
- Joining date

The dataset is included for educational and portfolio demonstration purposes. It does not represent actual employees or confidential company information.

## 7. How AI Was Used

One of the most valuable parts of this project was learning how AI can make analytical work more expandable and iterative.

An AI-assisted platform such as Julius AI can help users explore a dataset, test analytical directions and develop interactive visualizations more quickly. It can also make it easier to experiment with different ways of presenting information and refine an initial result through follow-up instructions.

However, **using AI effectively is not simply about entering a prompt and accepting whatever it generates**. The quality and relevance of the output depend heavily on how well the user understands the task and communicates it to the AI.

Some important lessons from this workflow:

- **Prompt with purpose:** A good prompt explains the dataset, the objective, the fields to consider and the expected output.
- **Provide context:** AI is more useful when it understands the business question and how the data should be interpreted.
- **Be specific:** Clear instructions about metrics, comparisons, chart types and dashboard layout can help guide the result.
- **Work iteratively:** The first output may not be the best. Reviewing it, identifying gaps and refining the prompt can lead to a more useful result.
- **Validate the output:** AI can misunderstand columns, make assumptions or produce misleading calculations. Its output should be checked against the source data.
- **Think creatively:** AI can suggest possibilities, but the user must decide which questions are meaningful, which comparisons are useful and how insights should be communicated.
- **Stay responsible:** AI is an assistant in the workflow, not a replacement for analytical thinking, data understanding or human judgment.

This project reinforced an important idea: **AI can expand what we are able to explore and build, but the real value comes from knowing how to guide it, question it, validate it and use it creatively.** Understanding how to work with AI is becoming just as important as knowing which tool to use.

## 8. Tools & Skills

| Tool / Skill | Application |
|---|---|
| Julius AI | AI-assisted data exploration and dashboard development |
| Microsoft Excel | Dataset storage and spreadsheet handling |
| Data analysis | Exploring workforce, compensation, performance and leave measures |
| Data visualization | Presenting information through charts and dashboard summaries |
| Prompt design | Communicating analytical requirements and refining AI-generated outputs |
| Critical review | Checking whether outputs and interpretations are relevant to the data |

## 9. Project Workflow

1. **Dataset review** – Reviewed the employee dataset, its fields and the types of questions the data could support.
2. **Analytical planning** – Organized the analysis into workforce overview, compensation, and performance and leave.
3. **AI-assisted exploration** – Used Julius AI to support data exploration and dashboard development.
4. **Prompt refinement** – Iteratively refined instructions to improve the relevance and presentation of the dashboard.
5. **Review and validation** – Reviewed whether the displayed information aligned with the dataset and whether the visualizations communicated the intended message.
6. **Publication** – Published the interactive dashboard and prepared this repository to document the project.

## 10. Repository Structure

```text
TechSpark-People-Intelligence/
│
├── README.md
├── Cleaned_Data.xlsx
└── screenshots/
    ├── workforce-overview.png
    ├── compensation-analysis.png
    └── performance-leave-analysis.png
```

The screenshot names shown above are suggested filenames. Add your actual dashboard screenshots to the `screenshots` folder when available.

## 11. How to Explore the Dashboard

1. Open the [published Julius AI dashboard](https://oxidized-tumbleweed-o2w.julius.site/?ref=P7K65GXNPT63&utm_source=shared_artifact).
2. Navigate through Workforce Overview, Compensation Analysis, and Performance & Leave Analysis.
3. Try the available filters and search controls.
4. Compare the views and consider what additional questions could be explored from the dataset.

## 12. Key Learnings

Through this project, I gained practical exposure to:

- Structuring an analytics project around clear business questions.
- Exploring employee-related data from multiple analytical perspectives.
- Developing an interactive dashboard with an AI-assisted tool.
- Writing and refining prompts to guide AI toward a specific analytical outcome.
- Reviewing AI-generated outputs rather than accepting them without validation.
- Communicating data through visual summaries and interactive exploration.
- Combining analytical thinking, curiosity and creativity with AI capabilities.

## 13. Limitations & Responsible Use

- The dataset is synthetic and created for educational and portfolio demonstration purposes.
- The dashboard should not be used to make actual hiring, compensation, promotion or employee-performance decisions.
- Observed patterns are descriptive and do not establish causation.
- AI-generated analysis and visualizations require human review and validation.
- No real employee records or confidential company information are intended to be represented.

## 14. Future Improvements

Possible extensions include:

- Adding a detailed data dictionary and metric definitions.
- Documenting data validation and cleaning rules.
- Adding deeper time-based comparisons where the dataset supports them.
- Including additional analytical questions and documented findings.
- Improving drill-downs and explanatory notes within the dashboard.
- Exploring reproducible analysis using SQL or Python alongside the AI-assisted workflow.

## Author

**Tharun U**  
Computer Science Engineering | Aspiring Data Analyst

Interested in data analytics, business insights, data visualization and the practical use of AI tools to solve analytical problems.

---

<div align="center">

**Thanks for visiting this project!**

I hope this project demonstrates how data, thoughtful prompting and human creativity can work together to turn raw information into an interactive analytical experience.

</div>
