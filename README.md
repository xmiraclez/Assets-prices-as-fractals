# Assets prices as fractals

Рекуррентный график цены биткоина из старого ноутбука: ячейка с заголовком Recurrence Graph of Bitcoin Price Patterns и ряд `data/BTC_1d.csv` (дневной Bitstamp, 2012-01-01 — 2024-08-26, 4622 строки).

```bash
pip install -r requirements.txt
jupyter notebook notebooks/bitcoin_recurrence.ipynb
```

Run All. Картинка: `output/bitcoin_recurrence_price_plot.png`.

![Recurrence Graph of Bitcoin Price Patterns](output/bitcoin_recurrence_price_plot.png)
