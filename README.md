
# Bitcoin Market Sentiment vs Trader Performance

## 📌 Objective
This project explores the relationship between **market sentiment (Fear vs Greed)** and **trader performance** (profitability, leverage usage, volume, and position sizing).  
The goal is to identify hidden behavioral patterns among traders under different sentiment regimes and extract insights to build smarter trading strategies.

---

## 🧠 Key Insights

| Aspect           | Fear Market                                    | Greed Market                                 |
|-----------------|-----------------------------------------------|---------------------------------------------|
| Profitability   | Lower variance but lower average returns       | Higher profits but higher volatility        |
| Leverage        | Conservative / stable                          | Higher, often aggressive                     |
| Trader Behavior | Risk-off, small positions                      | Risk-on, large exposure                      |
| Hidden Trend    | Contrarians outperform during fear             | Herding dominates outcomes                   |

✅ Sentiment often **leads** trading behavior by ~1 day  
✅ Smart strategies should **adjust risk based on sentiment regime**

---

## 📊 Visuals Included
- Line charts of sentiment vs PnL  
- Boxplots comparing PnL during fear/greed  
- Leverage distribution by sentiment  
- Rolling averages for lag analysis  

All plots are saved in the `/outputs/` folder.

---

## 🛠 How to Run Locally / On Colab

### On Colab (Recommended)
1. Upload the `csv_files/` folder to your session.  
2. Open `notebook_1.ipynb`.  
3. Run all cells.  
4. Outputs will be auto-saved in `/outputs/`.

### Local Setup
```bash
pip install pandas numpy matplotlib seaborn reportlab jupyter
jupyter notebook
````

### File Descriptions

| File             | Description                           |
| ---------------- | ------------------------------------- |
| notebook_1.ipynb | Full analysis code and visualizations |
| ds_report.pdf    | Final summary with insights           |
| csv_files/       | All raw and processed datasets        |
| outputs/         | All generated graphs                  |

