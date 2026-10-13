# 🏛️ Youth Confinement & Behavioral Data Analytics (CIYJ, 2025)

![Research Analytics](https://img.shields.io/badge/Focus-Research%20Analytics-blue)
![Youth Justice](https://img.shields.io/badge/Domain-Youth%20Justice-purple)
![Behavioral Data](https://img.shields.io/badge/Focus-Behavioral%20Data-lightgrey)
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab)

---

## 📊 Project Overview

This project examines the relationship between youth-reported confinement experiences and facility-reported confinement actions across 85 juvenile justice facilities during two collection periods: April 2025 and October 2025.

Using data from the CIYJ Youth Climate Survey and facility Incident Reports, the analysis investigates whether facilities recording more confinement actions also tend to have a higher percentage of youth reporting that they have been locked up because of misbehavior.

The project brings together two complementary perspectives:

- **Youth-reported experiences:** Survey responses about young people's experiences during their time in a facility.
- **Facility-reported records:** Incident Reports documenting confinement actions during each collection period.

The findings were translated into a practitioner-facing brief to support conversations about facility practices, youth experiences, and opportunities for further review.

This project was completed as part of a CIYJ externship through Extern.

---

## 🎯 Project Objectives

- Examine the relationship between youth-reported confinement experiences and facility-recorded confinement actions.
- Compare youth survey responses across facilities with different levels of recorded confinement.
- Assess whether the overall pattern appeared in both April and October 2025.
- Translate descriptive findings into actionable questions for practitioners.
- Communicate research findings and methodological limitations to a nontechnical audience.

---

## 🧠 Research Questions

1. Do facilities with more recorded confinement actions also have a higher percentage of youth reporting that they have been locked up because of misbehavior?
2. How do youth-reported experiences vary across facilities with different levels of recorded confinement?
3. Does the overall pattern appear in both collection periods?
4. How can comparisons between youth feedback and administrative records inform further facility review?

---

## 🗂️ Data Sources & Analytical Structure

### Youth Climate Survey

The analysis uses responses to the question:

> "Since you have been in this facility, have you ever been locked down because of misbehavior?"

For each facility and collection period, the analysis calculated the percentage of eligible respondents who answered "Yes." Responses of "Don't know" and "Refuse to answer" were excluded from the percentage calculation.

### Facility Incident Reports

Incident Reports document confinement actions recorded during each collection period. Facilities were grouped into four categories:

- 0 recorded actions
- 1–10 recorded actions
- 11–50 recorded actions
- 51 or more recorded actions

### Linking Survey and Administrative Data

The analysis compared facility-level survey percentages with recorded confinement categories for the corresponding collection periods.

The two measures capture different time frames: the survey asks about a youth's experience since entering the facility, whereas incident records cover the current collection period. They therefore provide complementary, but not directly equivalent, measures of confinement.

---

## 📏 Measures & Operational Definitions

| Measure | Definition |
|---|---|
| Youth-Reported Confinement | Percentage of eligible survey respondents answering "Yes" to the confinement question |
| Recorded Confinement Actions | Number of confinement actions documented in Incident Reports during the collection period |
| Confinement Category | Grouping based on recorded actions: 0, 1–10, 11–50, or 51+ |
| Collection Period | April 2025 or October 2025 |
| Facility-Level Comparison | Comparison of youth-reported confinement percentages across recorded-confinement categories |

---

## 🔄 Analytical Workflow

1. **Data review:** Examine the Youth Climate Survey and Incident Report data.
2. **Data preparation:** Organize relevant facility-level measures and identify eligible survey responses.
3. **Metric construction:** Calculate youth-reported confinement percentages and classify facilities by recorded actions.
4. **Comparative analysis:** Compare survey percentages across confinement categories.
5. **Cross-period assessment:** Examine whether the overall pattern appeared in both collection periods.
6. **Visualization:** Communicate the relationship between youth-reported experiences and facility records.
7. **Practitioner communication:** Translate findings, limitations, and follow-up questions into a practitioner-facing brief.

---

## 📈 Key Findings

Facilities with more recorded confinement actions generally had a higher percentage of youth reporting that they had been locked up because of misbehavior.

| Recorded Confinement Actions | Average Youth Reporting Confinement |
|---|---:|
| 0 actions | 31% |
| 1–10 actions | 54% |
| 11–50 actions | 55% |
| 51+ actions | 66% |

The overall pattern appeared in both April and October 2025, although results were not identical across every region or facility type.

These findings indicate an association between facility-recorded confinement and youth-reported experiences. They do not establish that recorded actions directly caused individual youth survey responses.

---

## 📊 Data Visualization

The project includes a scatter plot examining the relationship between youth-reported confinement and facility confinement records.

[View the confinement analysis visualization](https://glittery-vacherin-8619c0.netlify.app/Practitioner%E2%80%99s%20Brief_%20Youth%20Experience%20of%20Being%20Locked%20Up%20and%20Confinement%20Records_files/project_4_confinement_chart.png)

*Figure 1. Relationship between youth-reported confinement experiences and facility-reported confinement records.*

---

## 🏛️ Practitioner & Operational Implications

The findings offer a starting point for further facility review.

### Review confinement practices

Examine the circumstances in which confinement is used, the reasons documented, and the alternatives available when safe and appropriate.

### Investigate differences within facilities

Facility-wide totals may conceal differences between living units, incident types, confinement duration, and repeated involvement of particular youth.

### Compare administrative records with youth feedback

Comparing facility records with survey responses may help practitioners identify areas where documented practices and young people's experiences warrant closer examination.

### Support evidence-informed improvement

Potential areas for further review include staff coaching, de-escalation strategies, behavior-management practices, and opportunities for youth to return to regular programming.

These are potential avenues for investigation, not interventions whose effectiveness was established by this analysis.

---

## ⚠️ Limitations

- **Different time frames:** Youth survey responses cover experiences since entering a facility; Incident Reports cover the collection period.
- **Facility size:** The comparison does not adjust for the number of youth served by each facility.
- **Exposure differences:** The analysis does not account for how long surveyed youth had been at each facility.
- **Descriptive findings:** The observed relationship does not establish causation.
- **Facility variation:** The overall pattern was not identical across all regions and facility types.

The results should therefore be interpreted as descriptive comparisons, not causal estimates or standardized facility performance rankings.

---

## 🧰 Methods & Technical Stack

### Analytical Methods

- Survey-response percentage calculation
- Facility-level descriptive analysis
- Categorical comparisons
- Cross-period pattern assessment
- Data visualization
- Practitioner-oriented research communication

### Tools & Environment

The analysis notebooks are available through Google Colab. Specific programming languages, libraries, and statistical methods should be documented here once verified against the notebooks.

---

## 📚 Project Resources & Deliverables

The resources below provide access to the project's analysis notebooks and supporting documentation. They are organized by resource type to make it easier for recruiters and research collaborators to explore the work.

### 📓 Analysis Notebooks

**Analysis Notebook 1: Exploratory Data Analysis**

[Open in Google Colab](https://colab.research.google.com/drive/1oqbD8KCM_dqdH4-22us-KPpCiF6CSv5N?usp=sharing)

**Analysis Notebook 2: Linear Regression Analysis**

[Open in Google Colab](https://colab.research.google.com/drive/1utnliBN8tUZrNgrU8zE8WguGm4eX4Ecj?usp=sharing)

### 📄 Project Documentation

**Project Document 1: Data Visualization of the Correlation of Youth Reports of Being Locked Up & Total Confinement Time**

[Open Google Doc](https://docs.google.com/document/d/1n_BAAmsxT_0m9K2_Qbk4BXr1m15ctfST6XTLHlW8OdI/edit?tab=t.0)

**Project Document 2: Research Question**

[Open Google Doc](https://docs.google.com/document/d/1IA4DtbhxJKCklxSWAaVj_bejrpTwqWVKwvw1QpGlNw4/edit?tab=t.0)

**Project Document 3: Open Stress-Testing My Own Findings**

[Open Google Doc](https://docs.google.com/document/d/1OatuCDRCnoIhd2gStuBArC8d83Wz1YrnJ-MwStFnK04/edit?tab=t.0#heading=h.tu2rpj4f9drw)

---

## 📂 Repository Structure

```text
youth-confinement-analytics/
├── README.md
├── notebooks/
│   ├── analysis_notebook_1.ipynb
│   └── analysis_notebook_2.ipynb
├── visuals/
│   └── confinement_analysis.png
├── docs/
│   └── practitioner_brief.pdf
└── LICENSE
```

---

## 🙌 Acknowledgments

- CIYJ
- Extern

---

## 👩‍💻 Author

**Hana Gabrielle Bidon**

Research Analytics | Behavioral Data | Youth Outcomes | Public Interest Technology
