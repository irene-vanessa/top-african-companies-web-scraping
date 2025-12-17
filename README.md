## Data Scraping: Largest Companies in Africa by Revenue

This repository contains a Python project that scrapes and structures data from Wikipedia on the largest companies in Africa by revenue.

###  Project Objective
Real-world web scraping by extracting a structured HTML table and converting it into a clean CSV dataset suitable for analysis.

---

###  Technologies Used
- Python
- requests
- BeautifulSoup (bs4)
- pandas

---

###  Data Source
- Wikipedia: *List of largest companies in Africa by revenue*

---

###  Workflow
1. Send a compliant HTTP request with a custom User-Agent
2. Parse HTML using BeautifulSoup
3. Locate and extract table headers and rows
4. Convert scraped data into a pandas DataFrame
5. Export the dataset as a CSV file

---

### How to Use

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/african-companies-scraping.git
cd african-companies-scraping
```

2. **Install dependencies:**
```bash
pip install requests beautifulsoup4 pandas jupyter
```

3. **Run the notebook:**
```bash
jupyter notebook scraped_data.ipynb
```
---

###  Output
- **File**: `top_100_african_companies.csv`
- **Records**: 100 companies
- **Columns**: Rank, Company, Industry, Revenue (US$ billions), Headquarters
- **Data Year**: 2022
---

### Sample Data:
| Rank | Company | Industry | Revenue (US$ billions) | Headquarters |
|------|---------|----------|----------------------|--------------|
| 1 | Sonatrach | Oil and gas | 77.013 | Algeria |
| 2 | Eskom | Electric utility | 13.941 | South Africa |
| 3 | Sasol | Chemistry | 12.989 | South Africa |

---

###  Challenges Addressed
- Handling Wikipedia’s robot policy
- Correctly parsing HTML tables

---

###  What This Project Demonstrates
- Responsible web scraping practices
- HTML parsing and data cleaning
- Transforming unstructured web data into analysis-ready formats

---

###  Possible Improvements
- Add exploratory analysis or visualizations
- Automate updates with scheduling

---

###  Disclaimer
This project is for educational purposes only. All data belongs to Wikipedia and its contributors.

---

Connect with me: [LinkedIn](http://www.linkedin.com/in/irenevanessavifah) | [GitHub](https://github.com/irene-vanessa)

---

 **If you find this project useful, please consider giving it a star!**
