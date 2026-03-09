# Superstore-Sales-Analysis-Automated-Reporting
This project provides an end-to-end pipeline for analyzing retail sales data, generating dynamic HTML reports, and automating email distribution. It utilizes Python and Pandas to extract insights from a Superstore dataset and formats them into a professional stakeholder report.

 Features
Data Analysis: Processes sales records to calculate Total Sales, Sales Growth %, and identifies top-performing products and customers.
Dynamic Templating: Generates a clean, CSS-styled HTML email template with automated data injection.
Automated Emailing: A built-in SMTP module to send the generated report directly to recipients.
Missing Data Handling: Cleans datasets by managing null values in product margins.

 Technical Stack
Language: Python 3.x
Libraries: Pandas, Smtplib, Email.MIME
Data Source: Excel/CSV Superstore Sales Data

 Project Structure
analysis.ipynb: The main notebook containing the data processing logic.
weekly_sales_report.html: The generated output file ready for distribution.

 Setup & Usage
Prerequisites: Ensure you have pandas and openpyxl installed.
Configuration: Update the SMTP settings in the script with your provider's details (e.g., Gmail, Outlook).
Run: Execute the notebook to process the latest sales data and trigger the email report.
