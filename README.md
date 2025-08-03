# Web Scraping – Product Data Extraction Using Python

This project demonstrates how to use Python to scrape product data from a website. It's a beginner-friendly hands-on introduction to web scraping, extracting structured data from web pages and organizing it for analysis or reporting.

---

## 📌 Objective

To extract product-level information such as titles, prices, ratings, and availability from a sample website using Python libraries like `requests`, `BeautifulSoup`, and `pandas`.

---

## 🛠️ Tools and Libraries Used

- **Python 3**
- **Jupyter Notebook** – Development environment
- **requests** – To make HTTP calls and fetch webpage content
- **BeautifulSoup (bs4)** – To parse and extract HTML content
- **pandas** – To organize data into a structured format (DataFrame)
- **csv** – For exporting the data

---

## 🔍 What This Project Covers

- Sending GET requests to a website
- Parsing HTML content with BeautifulSoup
- Extracting relevant tags like product titles, prices, ratings, and more
- Structuring the extracted data into a DataFrame
- Exporting the final data to a `.csv` file

---

## 📊 Data Extracted

Depending on the target site and structure, the following fields were scraped:

- **Rank**
- **Name**
- **Industry** (if available)
- **Revenue (USD millions)**
- **Revenue growth**
- **Employees	Headquarters**

---

## 🧪 How to Run

1. Clone or download the repository
2. Install dependencies
3. Open the notebook in Jupyter
4. Run each cell step by step to scrape and process the data.
5. Exported CSV will be saved locally in the working directory.

---

## 📁 Project Structure

web-scraping-project/
├── web_scraping.ipynb # Main notebook with scraping code
├── products_data.csv # Sample output CSV file
└── README.md # Project documentation

---

## ⚠️ Legal and Ethical Note

Always review and respect a website’s `robots.txt` and terms of service before scraping. This project is for **educational purposes only**, and the target website used was publicly accessible with no login required.

---

## 👩‍💻 About Me

I'm an aspiring data analyst learning how to collect and work with real-world data. This web scraping project helped me understand how raw HTML content can be transformed into structured, analyzable datasets.

If you're a recruiter or fellow learner, feel free to connect or explore my other projects.

**GitHub**: [YourGitHubProfileLink]
