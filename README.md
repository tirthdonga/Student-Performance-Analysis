<div align="center">

# 🎓 Student Academic Performance Dashboard
### *Power BI Student Analytics & Interactive Dashboard Project*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-blue?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Education%20Analytics-1c6b4a?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Student%20Performance-2e9d70?style=for-the-badge)

**Power BI · Student Academic Performance Dashboard Project**

</div>

---

# 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Objective](#-objective)
- [📦 Data Model](#-data-model)
- [✨ Features](#-features)
- [🏗️ Repository Structure](#️-repository-structure)
- [🗂️ Report Pages](#️-report-pages)
  - [🎓 Page 1: Academic Performance](#-academic-performance)
  - [🧠 Page 2: Behavior](#-behavior)
- [🔍 Filters & Slicers](#-filters--slicers)
- [💡 Key Insights](#-key-insights)
- [🎨 Theme & Formatting](#-theme--formatting)
- [🛠️ Tools & Techniques](#️-tools--techniques)
- [🚀 How to Use This Project](#-how-to-use-this-project)
- [🎥 Video Walkthrough](#-video-walkthrough)
- [📈 Learning Outcomes](#-learning-outcomes)
- [👤 Author](#-author)

---

# 📌 Overview

The **Student Academic Performance Dashboard** is a Microsoft Power BI project designed to analyze student results, subject-wise performance, class-level averages and attendance.

The report interface includes two navigation options:

- 🎓 **Academic:** Displays student KPIs, subject and class comparisons, term-wise performance trends, and a student-wise performance table.
- 🧠 **Behavior:** A separate navigation option is visible in the dashboard. Displays attendance, behavior records, total absences, behavior-type distribution, attendance by class group, and student-wise behavior details.

The Academic view uses a green-and-white theme with KPI cards, interactive filters, charts and conditional formatting to make student performance easier to explore.

---

# 🎯 Objective

The main objective of this project is to build an interactive Power BI dashboard that helps analyze student academic performance.

The project focuses on:

- Monitoring the total number of students
- Tracking the average student score and attendance rate
- Comparing average scores across subjects and class groups
- Analyzing performance changes across academic terms
- Reviewing individual student scores and performance categories
- Filtering academic results by class, section, subject and term
- Presenting student performance information in a clear visual format

---

# 📦 Data Model

The Power BI Fields pane screenshot shows the following tables and measure group:

| Table / Group | Purpose |
|---|---|
| `Measures_1` | Measure group used for report calculations |
| `Attendance` | Student attendance information |
| `Behavior` | Student behavior-related information |
| `Scores` | Student assessment and score information |
| `Students` | Student details used in the report |

The model separates student details, scores, attendance and behavior data into individual tables to support the dashboard.

**Data source:** Student academic performance project data.

**Note:** The supplied screenshots do not show the original dataset source, source file names, row count, column definitions or complete table relationships. These details are not assumed in this documentation.

---

# ✨ Features

- 🎓 [**Total Students KPI**](#-academic-performance) — Displays the total student count.
- 📊 [**Average Score KPI**](#-academic-performance) — Displays the overall average score.
- 🟢 [**Attendance KPI**](#-academic-performance) — Displays the overall attendance percentage.
- 📚 [**Average Score by Subject and Class**](#-academic-performance) — Compares English, Geography, History, Math and Science across class groups.
- 📈 [**Performance Trend by Term**](#-academic-performance) — Tracks average performance across Term 1, Term 2 and Term 3.
- 📋 [**Student-Wise Performance Table**](#-academic-performance) — Displays student name, class, average score and performance category.
- 🎛️ [**Class Filter**](#-filters--slicers) — Filters the report by class.
- 🅰️ [**Section Filter**](#-filters--slicers) — Allows selection of Sections A, B and C.
- 📖 [**Subject Filter**](#-filters--slicers) — Filters by the available subjects.
- 🗓️ [**Term Filter**](#-filters--slicers) — Allows selection of T1, T2 and T3.
- 🎨 [**Conditional Score Formatting**](#-academic-performance) — Uses score colors to distinguish score ranges.
- 🧭 [**Academic / Behavior Navigation**](#️-report-pages) — Provides navigation between the two dashboard views.
- 🧠 [**Behavior KPIs**](#-behavior) — Attendance, behavior records, and absences.
- 🍩 [**Behavior Type Distribution**](#-behavior) — Compares five recorded behavior types.
- 📊 [**Attendance by Class Group**](#-behavior) — Compares attendance across class groups.
- 📋 [**Student-Wise Behavior Table**](#-behavior) — Shows attendance and behavior counts by student.

---

# 🏗️ Repository Structure

```text
📦 Student_Academic_Performance_Dashboard
│
├── 📊 Student Academic Performance Dashboard.pbix
│                                      → Power BI dashboard file
│
├── 📁 Assets
│   └── 📁 Images
│       ├── Academic_Performance.png  → Academic dashboard screenshot
│       └── Behavior.png              → Behavior dashboard screenshot
│
└── 📝 README.md                      → Project documentation
```

*The folder and screenshot names above are suggested names. Change them to match your actual project files and add your screenshots to the Assets/Images folder.*

---

# 🗂️ Report Pages

## 🎓 Academic Performance

The **Academic** view provides an overview of student academic results through KPI cards, subject comparisons, a term-wise trend and a detailed student table.

### KPI Cards

| KPI | Displayed Value |
|---|---:|
| 🎓 Total Students | 1,000 |
| 📊 Average Score | 49.9% |
| 🟢 Attendance | 90% |

### Visualizations

| Visual | Analysis |
|---|---|
| Average Score by Subject and Class | Compares English, Geography, History, Math and Science across Class 1–5, Class 6–10 and Class 11–12 |
| Performance Trend by Term | Shows average score movement across Term 1, Term 2 and Term 3 |
| Student-Wise Performance | Displays student name, class, average score percentage and performance category |

### Displayed Performance Details

- Term 1 average score: **49.7%**
- Term 2 average score: **49.6%**
- Term 3 average score: **50.3%**
- The subject chart compares five subjects across three class groups.
- The student table includes score-based cell formatting.
- The score legend identifies **Above 80%** and **Below 40%**.

### 📸 Dashboard Screenshot

Add your Academic dashboard screenshot to `Assets/Images/Academic_Performance.png`.

<img src="Assets/Images/Academic_Performance.png" alt="Student Academic Performance Dashboard">

---

## 🧠 Behavior

The **Student Behavior Dashboard** provides an overview of attendance, recorded student behaviors, absences, and individual student behavior information. It includes three KPI cards, a doughnut chart of behavior types, a class-group attendance chart, and a student-wise table.

### KPI Cards

| KPI | Value displayed |
|---|---:|
| 🟢 Attendance | 90% |
| 📝 Total Behavior Records | 6,500 |
| ❌ Total Absences | 9,952 |

### Visuals

| Visual | Analysis |
|---|---|
| Behavior Type Distribution | Doughnut chart showing Disruptive, Late, Helpful, Participative, and Absent without notice records (6,500 total) |
| Attendance % by Class Group | Compares attendance for Class 1–5, Class 6–10, and Class 11–12; all three bars appear around 90% |
| Student-Wise Performance | Table showing student name, class, attendance percentage, and behavior count |

*The doughnut chart's visible title reads “Avg Score by Subject and Class,” although its legend and values show behavior types. This README describes the content displayed rather than treating that title as an academic score chart.*

### Behavior Types

- Disruptive
- Late
- Helpful
- Participative
- Absent without notice

### Student-Wise Behavior Details

The table includes **Name**, **Class**, **Attendance %**, and **Behavior** columns. Visible examples include:

| Student | Class | Attendance | Behavior |
|---|---:|---:|---:|
| Alexander Kelly | 10 | 92% | 10 |
| Alicia Wilson | 4 | 88% | 10 |
| Amanda Nguyen | 5 | 86% | 10 |
| Amber Wagner | 2 | 90% | 10 |
| Amy Cisneros | 9 | 91% | 10 |

### Filters & Slicers

| Filter | Available options |
|---|---|
| Class | All or an individual class |
| Section | A, B, C |
| Gender | Female, Male |
| Behavior Type | Absent without notice, Disruptive, Helpful, Late, Participative |

### 📸 Dashboard Screenshot

Add your Behavior dashboard screenshot to `Assets/Images/Behavior.png`.

<img src="Assets/Images/Behavior.png" alt="Student Behavior Dashboard">

---

# 🔍 Filters & Slicers

The two dashboard views provide the following filtering controls:

| Filter | Available Options / Purpose |
|---|---|
| Class | All or an individual class |
| Section | A, B or C |
| Subject | English, Geography, History, Math and Science |
| Term | T1, T2 or T3 |

These controls allow users to explore student results across different classes, sections, subjects and academic terms.

---


# 💡 Key Insights

Based on the values visible in the supplied Academic dashboard screenshot:

- 🎓 The dashboard reports **1,000 total students**.
- 📊 The displayed overall average score is **49.9%**.
- 🟢 The displayed attendance rate is **90%**.
- 📈 Term 3 has the highest displayed term average at **50.3%**.
- 📉 Term 2 has the lowest displayed term average at **49.6%**.
- 📚 The subject comparison includes English, Geography, History, Math and Science.
- 📝 The Behavior dashboard displays **6,500 behavior records** and **9,952 total absences**.
- 🟢 The Behavior dashboard displays **90% attendance**, with similar attendance percentages across the three class groups.
- 🍩 The behavior distribution chart includes five categories: Disruptive, Late, Helpful, Participative, and Absent without notice.

*These observations are limited to the visible Academic and Behavior screenshots and their current filter selections.*

---

# 🎨 Theme & Formatting

### Design

- Dark green dashboard header
- Green-and-white report theme
- Gold accent color for selected navigation and chart markers
- Rounded KPI and chart containers
- Clear chart labels and data values
- Student table with conditional score formatting
- Left-side filter panel for quick report interaction

### Dashboard Layout

- **Header:** Dashboard title and Academic / Behavior navigation
- **Left panel:** Class, section, subject and term filters, plus score color legend
- **Top section:** Total Students, Average Score and Attendance KPI cards
- **Center section:** Subject-wise comparison and term performance trend
- **Bottom section:** Student-wise performance table

---

# 🛠️ Tools & Techniques

| Tool / Technique | Usage |
|---|---|
| **Microsoft Power BI** | Dashboard creation and data visualization |
| **Power Query** | Data preparation and transformation, where applied |
| **DAX** | Measures and calculated metrics |
| **Data Modeling** | Organizing student, score, attendance and behavior tables |
| **Slicers & Filters** | Interactive report filtering |
| **Conditional Formatting** | Highlighting student score ranges |
| **Charts & Tables** | Comparing academic results and displaying student details |

---

# 🚀 How to Use This Project

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. If Power BI requests a data source, update the source path to the dataset location.
4. Select **Refresh** if the source data has changed.
5. Use the Class, Section, Subject and Term filters to explore the Academic view.
6. Use the **Academic / Behavior** navigation buttons to switch report views.

---

# 🎥 Video Walkthrough

Add your project demonstration video link here.

`[Add YouTube or LinkedIn video link]`

---

# 📈 Learning Outcomes

Through this project, I practiced:

- Building an interactive Power BI dashboard
- Organizing multiple tables in a data model
- Creating and presenting KPI metrics
- Comparing subject-wise and class-wise performance
- Analyzing trends across academic terms
- Using slicers and navigation controls
- Applying conditional formatting to tables
- Presenting analytical findings through visualizations

---

# 👤 Author

<div align="center">

# Tirth Donga

[![GitHub](https://img.shields.io/badge/GitHub-Tirth_Donga-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tirthdonga)

**Student Academic Performance Dashboard | Power BI Project**

*Power BI · Student Data Analysis · Education Analytics*

---

### ⭐ Thank You For Visiting This Project ⭐

Made with ❤️ using Microsoft Power BI

</div>
