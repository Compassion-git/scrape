# 🕸️ VacancyMail Job Scraper

A Python project that scrapes the 10 most recent job listings from [VacancyMail](https://vacancymail.co.zw/jobs/), extracts key details, saves them in a structured CSV file, and (optionally) automates the scraping process on a schedule.

---

## 📦 Features

- ✅ Scrapes latest 10 job postings
- ✅ Extracts job title, company, location, expiry date, description, and job link
- ✅ Saves data to `scraped_data.csv`
- ✅ Logs events and errors to `scraper.log`
- ✅ Supports scheduled scraping (daily/hourly)

---

## 🛠️ Technologies Used

- `requests` – To make HTTP requests
- `beautifulsoup4` – To parse and extract data from HTML
- `pandas` – To structure and export data to CSV
- `schedule` – To optionally run the scraper on a schedule
- `logging` – To track progress and errors

---

## 📁 File Structure

