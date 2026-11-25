# India Historical Copper Prices Dataset (2004–2026, ₹ per kg) & Live Widget

Clean, structured historical copper reference prices in India expressed in **Indian Rupees per kilogram (₹/kg)**, compiled and maintained by **[CopperPrice.in](https://copperprice.in/)**.

## Live Reference & Interactive Tools

- **Live Copper Rate Today (₹/kg):** [https://copperprice.in/](https://copperprice.in/)
- **Interactive 10-Year & MAX Price Chart (2004–2026):** [https://copperprice.in/copper-price-chart/](https://copperprice.in/copper-price-chart/)
- **Full Historical Tables & CSV Downloads:** [https://copperprice.in/copper-price-history/](https://copperprice.in/copper-price-history/)
- **Copper Weight & Budget Calculator (1g, 100g, 1kg, 1 tonne):** [https://copperprice.in/copper-price-calculator/](https://copperprice.in/copper-price-calculator/)
- **Rolling Returns, Volatility & Drawdown Analysis:** [https://copperprice.in/copper-price-analysis/](https://copperprice.in/copper-price-analysis/)
- **Indian Copper Grades & BIS Standards (IS 191, ETP, OFC, Scrap):** [https://copperprice.in/copper-grades-india/](https://copperprice.in/copper-grades-india/)
- **Indian Copper Industry Overview (Supply, Imports, Capacity):** [https://copperprice.in/copper-industry-india/](https://copperprice.in/copper-industry-india/)

---

## Included CSV Files

All prices are in **INR per kg (`₹/kg`)** with IST calendar boundaries (`Asia/Kolkata`).

| File | Granularity | Coverage | Columns |
|---|---|---|---|
| `data/copper_price_india_yearly.csv` | Yearly | 2004–2026 (23 years) | `period, period_start, period_end, open, high, low, close, average, change, change_percent, trading_days, complete` |
| `data/copper_price_india_quarterly.csv` | Quarterly | 2004–2026 (91 quarters) | `period, period_start, period_end, open, high, low, close, average, change, change_percent, trading_days, complete` |
| `data/copper_price_india_monthly.csv` | Monthly | Latest 240 months (20 years) | `period, period_start, period_end, open, high, low, close, average, change, change_percent, trading_days, complete` |
| `data/copper_price_india_daily_recent.csv` | Daily | Latest 366 trading sessions | `date, open, high, low, close, average, change, change_percent, volume, complete` |

---

## Embed the Live India Copper Price Widget

You can embed a lightweight, live India copper price card on any website or blog using the official widget from CopperPrice.in:

```html
<iframe
  src="https://copperprice.in/widget/"
  title="Copper Price Today in India (₹/kg) — CopperPrice.in"
  width="340"
  height="180"
  style="border:0;max-width:100%;border-radius:12px;"
  loading="lazy"
></iframe>
<p style="font-size:12px;margin-top:4px;">
  Live rate by <a href="https://copperprice.in/">CopperPrice.in</a>
</p>
```

---

## Notes & Disclaimer

- The published series represents an exchange-traded copper futures reference in Indian rupees per kilogram, not a guaranteed local scrap, retail, or city-specific dealer quote.
- For methodology and data quality documentation, see [CopperPrice.in Data Coverage](https://copperprice.in/copper-price-data/).

## License & Attribution

Published under **CC BY 4.0**. When using this dataset in articles, notebooks, dashboards, or research, please attribute **[CopperPrice.in](https://copperprice.in/)**.
