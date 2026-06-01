# Car Sales Data Automation

An automated Python pipeline that parses car sales data from a JSON format, calculates sales performance metrics, generates a dynamic vector PDF report (complete with tables and visual data charts), and automatically emails the results.

## Features
- **Data Parsing:** Reads and converts JSON sales telemetry using Python's `locale` and `collections` modules.
- **Advanced Insights:** Tracks highest revenue-generating models, top-selling vehicles, and identifies the most popular sales years.
- **Custom ReportLab PDF:** Dynamically generates a summary PDF featuring a sorted performance layout and an automated pie-chart breakdown of total sales by car manufacturer.
- **Automated Emailing:** Constructs and dispatches email payloads containing the compiled text blocks and PDF attachments.

## Project Structure
- `cars.py`: The core automation engine handling analysis and workflow logic.
- `reports.py`: Internal module handling basic layout and document building blocks.
- `emails.py`: Internal system setting up SMTP configurations and attachment headers.

## Setup & Execution
1. Clone this repository:
   ```bash
   git clone [car-sales-automation](https://github.com/your-adeniranprecious002-ux/car-sales-automation.git)
