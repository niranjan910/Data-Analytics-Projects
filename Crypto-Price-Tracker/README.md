# Crypto Price Tracker (Bitcoin)

## Project Overview
---
This project is a **real-time Bitcoin (BTC) price tracker** built in Python.  
It fetches live price data from the **CoinGecko API**, updates every minute, visualizes the trend in a chart, and generates alerts when Bitcoin price moves by more than a defined threshold (default ±5%).  

---

## Features
---
- Fetch live Bitcoin price using CoinGecko API  
- Real-time updates every N seconds (configurable)  
- Automatic chart updates in Jupyter Notebook  
- Alerts when price moves ±X% from baseline  
- Saves all data points into CSV files for later analysis  
- Error handling and graceful termination  

---

## Data Source
---
**API Provider**: [CoinGecko Public API](https://www.coingecko.com/en/api)  

**Endpoint Used:**
[End Point](https://api.coingecko.com/api/v3/simple/price?ids=bitcoin&vs_currencies=usd).

**Sample JSON Response:**
```json
{
  "bitcoin": {
    "usd": 25874
  }
}
```

## Data Pipline 
1. **Data Collection**- Fetch BTC price at fixed intervals via API
2. **Data Processing** - Append timestamp + price to Pandas DataFrame
3. **Visualization** - Live chart plotting using Matplotlib
4. **Alerts** - Price % change vs baseline checked; alerts triggered if threshold exceeded
5. **Persistence** - Data continously saved to csv
6. **Output** - Console logs + charts updates in real time

#### **Pipline Flow :**
CoinGecko API → Python Requests → Pandas DataFrame
                        ↓
                Matplotlib Chart
                        ↓
              Alerts + CSV Storage

## Installation 
#### Installation dependencies 
```
pip install request pandas matplotlib
```

### Run jupiter notebook 
```
jupiter notebook

```

