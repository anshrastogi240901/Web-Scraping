# CBSE SARAS – State-wise School Scraper (Uttar Pradesh) 
# State name can be changed to any other by Replacing UTTAR Pradesh

This project automates the extraction of **CBSE-affiliated school data** from the official **CBSE SARAS directory** for **Uttar Pradesh** using **Python + Selenium**.

The scraper replicates the exact manual steps performed on the website:
1. Select **State Wise** search
2. Choose **Uttar Pradesh**
3. Click **Search**
4. Scrape **all paginated results**
5. Export data to **CSV**

---

## 📌 Website Scraped
https://saras.cbse.gov.in/saras/AffiliatedList/ListOfSchdirReport

---

## 📊 Data Extracted

For **each school**, the scraper extracts the following **7 columns** exactly as displayed on the website:

1. S NO  
2. AFF. NO & SCHOOL CODE  
3. STATE & DISTRICT  
4. STATUS  
5. SCHOOL & HEAD NAME  
6. ADDRESS  
7. DETAILS  

Total records scraped: **~4674 schools (Uttar Pradesh)**

---

## 🛠️ Tech Stack

- Python 3.9+
- Selenium
- ChromeDriver
- CSV (output)

---

## ⚙️ Setup Instructions

### 1️⃣ Install Required Packages (Run once only)
```bash
pip install selenium
