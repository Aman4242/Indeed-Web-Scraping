# 🕸️ Indeed Job Listings Web Scraping using Selenium

This project scrapes job listings from **Indeed India** using Selenium WebDriver. It automates the process of collecting job data based on a given job title and location, saving the results in a structured CSV file for analysis or personal job tracking.

---

## 📌 Project Overview

- Automates job search on [Indeed](https://in.indeed.com) for a specific job title and location.
- Collects information like:
  - Job Title
  - Company Name
  - Job Location
  - Salary (if available)
  - Direct Job Link
- Outputs the results into a CSV file.

---

## 📊 Data Collected

Each job listing includes:

- Title – Job title
- Company – Company name
- Job Location – City/region
- Salary – If listed, otherwise marked as "Unpaid"
- Link – URL to the job posting

---

## 🛠️ Technologies Used

- **Python** – Core scripting language
- **Selenium** – Web automation and interaction
- **WebDriver Manager** – Automatically manages ChromeDriver
- **Pandas** – For data organization and CSV export

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/aman4242indeed-job-scraper.git
cd indeed-job-scraper
Sample Output (CSV Preview)
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
requirements.txt:
```nginx
selenium
webdriver-manager
pandas
```
### 3. Run the Scraper
Edit the last line of the script to set your job search parameters:
``` python
scrape_indeed_jobs("Data Scientist", "New Delhi, Delhi", num_pages=6)
Then run the script:
```
``` bash
python indeed_scraper.py
```
The output file indeed_jobs.csv will be generated in the project directory.

## Sample Output (CSV Preview)
Title             	Company	           Job Location	          Salary             	Link
Data Scientist    	ABC Solutions	     New Delhi, Delhi    	₹15,00,000     	https://in.indeed.com/viewjob?jk=abc123
ML Engineer	        XYZ Analytics	         Delhi	            Unpaid	      https://in.indeed.com/viewjob?jk=xyz456

## Future Enhancements
  - Scrape detailed job descriptions from individual job pages.
  - Support multiple countries/domains (e.g., .com, .uk, .ca).
  - Build a dashboard to analyze job trends using Streamlit or Power BI.
  - Schedule regular scrapes using cron jobs or task schedulers.

## Disclaimer
- This project is for educational purposes only. Please ensure your use complies with Indeed's Terms of Service. Excessive or aggressive scraping may result in IP bans.

🔗 Connect
GitHub: [My GitHub Profile](https://github.com/Aman4242)
LinkedIn: [My LinkedIn Profile](in/aman-kumar-a51776224)
