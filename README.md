# E-commerce Web Scraping Demo 🛒

This project demonstrates how to scrape structured product data from a mock
e-commerce website using **Python**, **Requests**, and **BeautifulSoup**.

The target site is a public **web scraping test site**, intended for learning
and practice.

---

## 📌 Project Overview

- Scrapes laptop product data from a test e-commerce website
- Extracts structured data stored in HTML `data-*` attributes
- Converts extracted data into a Pandas DataFrame
- Saves the results as a CSV file

---

## 🔧 Technologies Used

- Python
- Requests
- BeautifulSoup (lxml parser)
- Pandas
- JSON

---

## 🚀 How It Works

1. Sends an HTTP request with a browser-like User-Agent
2. Parses the HTML using BeautifulSoup
3. Locates elements containing `data-type` attributes
4. Extracts JSON data from `data-items`
5. Converts the data into a Pandas DataFrame
6. Saves the data to `Laptops.csv`

---

## ⚠️ Disclaimer
This project is for educational purposes only.
The website used is a public test site designed specifically for web scraping practice.



