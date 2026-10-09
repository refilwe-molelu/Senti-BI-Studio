# SentiBI — AI-Powered Business Intelligence Assistant

**Turning spreadsheet data into meaningful business insights.**

SentiBI is an interactive Business Intelligence prototype designed to simplify the journey from raw data to actionable insights. It brings data profiling, data quality checks, sentiment analysis, visualisation, and AI-assisted recommendations into one guided workspace.

The goal is to reduce repetitive analytical work while keeping the analyst in control of data validation, interpretation, and business decisions.

> **SentiBI does the heavy lifting. The analyst stays in control.**

## Table of Contents

* [Overview](#overview)
* [The Problem](#the-problem)
* [Project Objectives](#project-objectives)
* [Key Features](#key-features)
* [How It Works](#how-it-works)
* [Technology Stack](#technology-stack)
* [Getting Started](#getting-started)
* [Example Use Case](#example-use-case)
* [Human-in-the-Loop Approach](#human-in-the-loop-approach)
* [Current Limitations](#current-limitations)
* [Future Development](#future-development)
* [Project Status](#project-status)

## Overview

Business data is often spread across spreadsheets and multiple analytical tools. Preparing, cleaning, exploring, visualising, and interpreting this data can take significant time before meaningful decisions can be made.

SentiBI explores how these steps can be brought together in one accessible workspace.

Although sentiment analysis is one of its capabilities, SentiBI is designed as a broader Business Intelligence assistant that can support different stages of the data analysis process.

## The Problem

Analysts and business teams may face challenges such as:

* Spending too much time on repetitive data preparation.
* Identifying missing values, duplicates, and inconsistent fields.
* Turning raw spreadsheet data into meaningful visualisations.
* Analysing large volumes of customer feedback.
* Connecting findings to practical business actions.
* Explaining and validating the assumptions behind analytical results.

SentiBI aims to make the initial stages of this process easier, more transparent, and more accessible.

## Project Objectives

* Simplify spreadsheet-based data exploration.
* Identify potential data quality issues early.
* Suggest useful field roles, measures, and analytical directions.
* Explore customer sentiment and recurring feedback themes.
* Present findings through interactive dashboards.
* Generate recommendations that users can investigate.
* Preserve human oversight throughout the analytical process.

## Key Features

### 1. Data Upload and Preview

* Import Excel and CSV files.
* Preview records and inspect available columns.
* Review basic dataset information.

### 2. Data Quality Checks

* Identify missing values.
* Detect exact duplicate rows.
* Highlight blank records.
* Profile columns and distinct values.

### 3. BI Model and KPI Suggestions

* Suggest field roles such as dates, categories, identifiers, text, and numeric measures.
* Identify potential measures and dimensions.
* Export a starter model specification for further development.

### 4. Sentiment Analysis

* Apply transparent, keyword-based rules to written feedback.
* Categorise feedback as positive, neutral, or negative.
* Highlight recurring terms.
* Allow analysts to review and override sentiment labels.

### 5. Interactive Dashboard

* Display dataset summary metrics.
* Explore numeric summaries and category breakdowns.
* Visualise sentiment patterns.

### 6. Business Insights and Recommendations

* Surface potential patterns and data issues.
* Suggest follow-up questions and possible actions.
* Generate a text-based executive briefing.

### 7. Analyst Review Centre

* Track validation checks.
* Document assumptions and business context.
* Export analyst notes before sharing results.

## How It Works

The current prototype follows a guided workflow:

1. **Upload** — Import an Excel or CSV dataset.
2. **Profile** — Inspect the dataset and identify basic quality issues.
3. **Map** — Review suggested field roles.
4. **Analyse** — Explore numeric data and, where relevant, written feedback.
5. **Visualise** — Examine summary charts and category patterns.
6. **Investigate** — Review possible findings and suggested next steps.
7. **Validate** — Correct labels, check assumptions, and confirm definitions.
8. **Export** — Download data, model specifications, notes, and an executive briefing.

## Technology Stack

The current prototype uses:

* **HTML5** — Application structure.
* **CSS3** — Styling and responsive layout.
* **JavaScript** — Application logic and interactive features.
* **SheetJS (xlsx)** — Excel workbook reading.
* **Chart.js** — Interactive data visualisations.
* **CSV processing** — Spreadsheet data import and export.
* **JSON** — Exporting a starter BI model specification.

External JavaScript libraries are loaded through CDNs, so an internet connection is required for those library-dependent features.

## Getting Started



3. Open `file:///C:/Users/CAPACITI-JHB/Downloads/SentiBI_Studio%20(3).html` in a modern web browser.


## Example Use Case

### Understanding Customer Feedback

Imagine a business receives customer feedback through reviews, surveys, and support tickets.

SentiBI can help the team:

1. Upload a spreadsheet containing customer feedback.
2. Inspect missing values and duplicate records.
3. Apply initial sentiment labels to written comments.
4. Identify recurring words and potential problem areas.
5. Review and correct automated labels.
6. Explore patterns alongside available categories.
7. Generate a summary of findings and possible next steps.

For example, repeated mentions of delayed deliveries could prompt a review of fulfilment performance.

However, the feedback alone does not prove the underlying cause. The analyst must investigate the source records and relevant operational data before recommending a final action.

## Human-in-the-Loop Approach

SentiBI is being developed around a central principle:

**AI prepares. The analyst validates. The business decides.**

Automation should support analysts, not remove their responsibility.

The intended approach prioritises:

* Transparent analytical logic.
* Human review of uncertain results.
* Editable sentiment classifications.
* Validation of business metrics and assumptions.
* Evidence-based recommendations.
* Clear communication of limitations.

## Current Limitations

SentiBI is currently an interactive prototype and proof of concept.

The current implementation does **not** yet provide:

* A trained AI or transformer-based sentiment model.
* Advanced causal root-cause analysis.
* Live Power BI publishing or authentication.
* Automatic creation and validation of a complete Power BI model.
* Guaranteed preservation or execution of source Excel formulas.
* Production-grade user management, security, or audit logging.

Sentiment analysis currently uses keyword-based rules. Findings are exploratory and should be validated before they are used to make business decisions.

## Future Development

Planned areas for exploration include:

* More advanced data profiling and validation.
* Improved explanations of analytical results.
* Integration with genuine AI and language models.
* More robust sentiment analysis and topic detection.
* Expanded KPI and dashboard generation.
* Power BI model and workflow integration.
* Stronger privacy, security, and governance controls.
* User testing to evaluate usability, accuracy, and time saved.

These are development goals, not claims about existing functionality.

## Project Status

**Status:** Interactive prototype / proof of concept.

SentiBI is an evolving project exploring how AI-assisted analytics can make business intelligence more accessible, transparent, and useful.

Feedback, ideas, and suggestions for improvement are welcome.

---

*Built to explore the intersection of Business Intelligence, Data Analytics, and AI Engineering.*

**SentiBI — Make data easier to understand.**
# Senti-BI-Studio
