# Car Sales Data Automation

An end-to-end Python automation project that processes car sales data from JSON files, analyzes key business metrics, generates professional PDF reports with visualizations, and automatically emails the results to stakeholders.

Built as part of the **Google IT Automation with Python Professional Certificate**, this project demonstrates data processing, report generation, and workflow automation using Python.

---

## Overview

The automation pipeline performs the following tasks:

1. Reads and parses car sales data from a JSON dataset.
2. Calculates important sales performance metrics.
3. Generates a professional PDF report with charts and summary statistics.
4. Sends the generated report automatically via email.

This workflow simulates a real-world business reporting system where sales data is transformed into actionable insights and distributed automatically.

---

## Features

### Data Processing

* Parses car sales records from JSON files.
* Formats currency values using Python's `locale` module.
* Aggregates and analyzes sales information using `collections`.

### Sales Analytics

The system identifies:

* The vehicle that generated the highest revenue.
* The best-selling vehicle based on total sales.
* The most popular manufacturing year.
* Overall sales trends across manufacturers.

### Automated PDF Reporting

Generates a dynamic PDF report using ReportLab that includes:

* Executive summary of key findings.
* Sales performance tables.
* Revenue statistics.
* Pie chart visualization showing manufacturer sales distribution.

### Email Automation

* Automatically composes email messages.
* Attaches generated PDF reports.
* Sends reports to recipients using SMTP.

---

## Project Structure

```text
car-sales-automation/
│
├── cars.py          # Main automation workflow and sales analysis
├── reports.py       # PDF report generation using ReportLab
├── emails.py        # Email creation and delivery functions
├── data/            # Input JSON sales data
├── tmp/             # Generated reports
└── README.md
```

---

## Technologies Used

* Python 3
* JSON
* ReportLab
* SMTP Email Services
* locale
* collections
* email package

---

## Installation

Clone the repository:

```bash
git clone https://github.com/adeniranprecious002-ux/car-sales-automation.git
cd car-sales-automation
```

Install dependencies:

```bash
pip install reportlab
```

---

## Running the Project

Execute the main automation script:

```bash
python3 cars.py
```

The script will:

1. Analyze the sales dataset.
2. Generate a PDF summary report.
3. Create visual sales charts.
4. Email the completed report automatically.

---

## Example Insights Generated

The report automatically highlights information such as:

```text
The Toyota Corolla generated the most revenue: $1,250,000

The Honda Civic had the highest number of sales: 320

The most popular manufacturing year was 2018 with 780 sales
```

---

## Learning Objectives

This project demonstrates practical skills in:

* Python automation
* Data analysis
* JSON processing
* Report generation
* Business intelligence reporting
* Email automation
* Workflow orchestration

---

## Future Improvements

* Interactive web dashboard for sales visualization.
* Database integration for persistent storage.
* Scheduled report generation using cron jobs.
* Support for CSV and Excel datasets.
* Cloud deployment and email notifications.

---

## Author

**Precious Adeniran**

Created as part of the **Google IT Automation with Python Professional Certificate** and expanded as a portfolio project demonstrating automation, reporting, and business analytics workflows.
