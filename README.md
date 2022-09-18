# mod11c
### Package Requirments & Versions
`pip install x` x represents below packages
* `python`
* `pandas`
* `pystan`
* `prophet`
* `hvplot`
* `holoviews`

### Purpose of Use
* Analyze MercadoLibre's financial and user data by finding out if ability to predict traffic can translate into ability to trade the stock successfully.

* The code is multiple parts:
    1. Finding unusual patterns in hourly Google search traffic
    2. Mining search traffic data for seasonality
    3. Relating search traffic to stock price patterns
    4. Creating time series model with Prophet
    
### Files Navigation
* `forecasting_net_prophet.ipynb`: Code explanation and building
* `google_hourly_search_trends.csv`
* 'mercado_daily_revenue.csv'
* 'mercado_stock_price.csv'