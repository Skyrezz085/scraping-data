# Seblak Tokopedia Scraping 🍲🛒
Scrape product data for "seblak" from Tokopedia using Selenium and BeautifulSoup, storing product names, prices, and shop names for analysis or business insights.

## Introduction 🌍
Seblak, a popular spicy dish from Indonesia, has a significant online market presence. Understanding the distribution, pricing, and vendors selling seblak products on e-commerce platforms like Tokopedia can provide valuable market insights for businesses, researchers, and culinary enthusiasts.  
This project automates data extraction for seblak-related products, creating a structured dataset to support further analysis.

## Dataset Overview 📊
The dataset consists of scraped product data from Tokopedia, an Indonesian online marketplace.  
Fields collected:
- `Nama Produk`: The name of the seblak product.
- `Harga`: The listed price of the product.
- `Nama Toko`: The seller's or shop's name.

### Data Source
- Website: [Tokopedia - Seblak Search Results](https://www.tokopedia.com/search?q=seblak&source=universe&st=product&srp_component_id=02.07.01.01)

## Methodology 🔍
1. **Web Driver Setup**: Initialize a headless Chrome WebDriver for automated browsing.
2. **Scrolling and Loading**: Automate page scrolling to load all seblak products.
3. **HTML Parsing**: Parse the page source using BeautifulSoup.
4. **Data Extraction**: Find product name, price, and shop name with proper error handling.
5. **Data Storage**: Store extracted data into a structured Pandas DataFrame.
6. **Export**: Save the dataset into a CSV file for further use.

## Project Objectives 🎯
Develop an automated scraping tool to:
- Collect real-time product listings related to seblak from Tokopedia.
- Provide clean, structured data for further market analysis.
- Enable businesses and researchers to monitor pricing and vendor dynamics easily.

## Output File 📂
- **File Name**: `data_seblak.csv`
- **Contents**: All products found for the keyword *seblak* on Tokopedia.

## Project Strengths and Weaknesses 🧮
### Strengths 💪
- **Automation**: Collects large amounts of product data with minimal manual intervention.
- **Headless Operation**: Runs silently without opening browser windows, efficient for batch scraping.
- **Simple and Scalable**: Can be adapted to scrape different keywords or categories with minor changes.

### Weaknesses ⚠️
- **Dynamic Website Challenge**: Changes in Tokopedia's site structure may break the scraping script.
- **Incomplete Data Risk**: Some products may have missing fields if not handled carefully.
- **Rate Limiting**: Excessive requests may trigger blocks if scraping aggressively without delays.

### Improvements 🔧
To enhance the scraper:
- **Error Resilience**: Implement more sophisticated retry mechanisms.
- **Scrape Additional Fields**: Add more product attributes like ratings, stock availability, etc.
- **Pagination Support**: Handle multiple pages systematically for even larger datasets.
- **Proxy Usage**: Use rotating proxies or user agents to avoid potential IP bans.

## Conclusion 📈
The Seblak Tokopedia Scraper provides a lightweight, effective tool for collecting product data from Tokopedia. While it currently focuses on a specific keyword (*seblak*), the framework can be expanded to other categories, helping businesses and researchers stay updated with market dynamics.

## Libraries Used 🛠️
- Pandas
- Selenium
- BeautifulSoup
- Time

## Author 👨‍💻
Reza Syadewo  
LinkedIn: [Reza Syadewo](https://www.linkedin.com/in/reza-syadewo-b5801421b/)  
Email: syadeworeza1705@gmail.com
