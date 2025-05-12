# 📚 Book Scraper – Web Scraping Project (Week 3)

> ✅ This project is part of my 4-week challenge to master Web Scraping and Data Analysis with Python.

---

## 🧠 Project Summary

This scraper collects book information from the public website [Books to Scrape](https://books.toscrape.com/), which is ideal for learning and practicing web scraping.

The scraper extracts key data from the homepage including:

- **📘 Book Title**
- **💲 Price**
- **📦 Availability**
- **🔗 Link to Detail Page**

---

## 🔧 Technologies Used

| Tool | Purpose |
|------|---------|
| Python 🐍 | Main programming language |
| Playwright (async) 🎭 | Web automation and scraping |
| Pandas 🧮 | Data manipulation and saving to CSV |
| Matplotlib 📊 | Visualizing the data |
| Google Colab ☁️ | Cloud-based development |
| Git & GitHub 🔁 | Version control and portfolio publishing |

## 💡 Key Skills Practiced:

✅ Using asynchronous scraping with Playwright
✅ Waiting for elements using selectors
✅ Structuring and cleaning data with Pandas
✅ Creating and saving charts
✅ Writing clean and reusable code
---

## 📊 Sample Output

Here is a snapshot of the collected data:

| Title                         | Price | Availability | Link |
|------------------------------|--------|---------------|------|
| A Light in the Attic         | £51.77 | In stock      | 🔗 |
| Tipping the Velvet           | £53.74 | In stock      | 🔗 |
| Soumission                   | £50.10 | In stock      | 🔗 |

---

## 📈 Visualization

![Bar Chart of Book Prices](book_prices_plot (3).png)

> A clear view of price differences among the first 10 books.

---

## 📌 How to Run the Project

### 1. On Google Colab:
- Upload `book_scraper.ipynb`
- Run all cells
- Download or view:
  - CSV output
  - Price chart

### 2. Local Requirements:
```bash
 pip install playwright pandas matplotlib nest_asyncio
 playwright install



