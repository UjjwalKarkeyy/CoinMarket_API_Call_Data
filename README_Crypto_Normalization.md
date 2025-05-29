# 💹 Cryptocurrency API Normalization with Python

This project demonstrates how to fetch live cryptocurrency data from the CoinMarketCap API and convert the nested JSON into a readable DataFrame using `pandas.json_normalize()`. It's a great starting point for working with real-time API data and preparing it for analysis.

---

## 📁 Repository Structure

```
crypto-normalization/
├── main.ipynb                         # Original notebook + Documented
└── README.md                          # Project overview
```

---

## 🧰 Libraries Used

- `requests` – to make API calls
- `pandas` – to flatten and process JSON

Install them with:
```bash
pip install requests pandas
```

---

## 🔑 API Key Required

Sign up at [CoinMarketCap](https://coinmarketcap.com/api/) to get your API key.  
Update this in the headers before sending the request:
```python
headers = {
    'Accepts': 'application/json',
    'X-CMC_PRO_API_KEY': 'your_api_key_here'
}
```

---

## 🚀 What It Does

- Sends an HTTP GET request to CoinMarketCap's `cryptocurrency/listings/latest` endpoint
- Receives data in nested JSON format
- Normalizes the JSON to flat tabular form using `pandas.json_normalize`
- Outputs a DataFrame for analysis

---

## 🔍 Sample Use Cases

- Crypto market monitoring
- Data wrangling from APIs
- Learning how to parse and normalize JSON

---

## 👨‍💻 Author

**Ujjwal Karki**  
Learning data one API at a time 📡📊

---