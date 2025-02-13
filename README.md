# E-commerce Price Tracker

## About
Developed a web application that displays real-time product prices from the official e-commerce company **Amazon**. Web scraping is implemented using two methods:

- **BeautifulSoup** and **requests**
- **Scrapy API**

## Features
- Fetches real-time product prices from Amazon.
- Uses **BeautifulSoup** and **requests** for lightweight scraping.
- Implements **Scrapy API** for scalable and efficient data extraction.
- Displays product details dynamically on the web application.

## Technologies Used
- **Python**
- **Flask** (for backend web application)
- **BeautifulSoup** and **requests** (for basic web scraping)
- **Scrapy** (for advanced and scalable scraping)
- **JavaScript, HTML, CSS** (for frontend)
- **Firebase** (for storing scraped product data)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ecommerce-price-tracker.git
    cd ecommerce-price-tracker
    ```

2. **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use: env\Scripts\activate
    pip install -r requirements.txt
    ```

3. **Run the Scraper:**
    - Using BeautifulSoup:
      ```bash
      python scrape_bs.py
      ```
    - Using Scrapy:
      ```bash
      scrapy crawl amazon_spider
      ```

4. **Start the Web Application:**
    ```bash
    python app.py
    ```
    Access the web application at `http://127.0.0.1:5000/`.

## Usage
- Enter the **Amazon product URL** in the input field.
- Click the **Fetch Price** button.
- The real-time price and product details will be displayed.
- The latest fetched data is stored in Firebase.

## License
This project is licensed under the MIT License. Feel free to modify and distribute it.
