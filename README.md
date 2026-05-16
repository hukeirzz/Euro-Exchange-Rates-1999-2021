# 💶 Storytelling Data Visualization: Euro Exchange Rates (1999–2021)

## 📖 Project Overview
Data visualization is more than just plotting points; it's about communicating insights that drive understanding. This project explores the historical volatility of the **Euro (EUR)** against the **US Dollar (USD)** and other global currencies over a 22-year period. 

Using data from the **European Central Bank**, this analysis moves from exploratory data cleaning to explanatory storytelling, highlighting how major geopolitical and economic events shaped the currency market.

## 🎯 Key Objectives
* **Data Wrangling**: Cleaning and transforming irregular time-series data (handling missing values, format conversion, and filtering).
* **Trend Analysis**: Utilizing **Rolling Averages** to smooth out daily volatility and reveal long-term economic trends.
* **Information Design**: Applying the **Data-Ink Ratio** and **Gestalt Principles** to create professional, journalistic-style visualizations (inspired by FiveThirtyEight).
* **Storytelling**: Comparative analysis of exchange rate fluctuations across different eras, including the 2008 Financial Crisis and various US Presidential administrations.

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **Libraries**: 
    * `Pandas`: Data manipulation and cleaning.
    * `Matplotlib`: Core visualization engine.
    * `Datetime`: Time-series handling.
* **Style**: FiveThirtyEight aesthetic for explanatory clarity.

## 📊 Dataset Highlights
The dataset contains daily exchange rates for the Euro against 40+ currencies.
* **Timeline**: January 1999 to January 2021.
* **Source**: European Central Bank (ECB) via Kaggle.
* **Complexity**: Requires handling "null" values represented as strings and non-trading days (weekends/holidays).

## 📈 Planned Visual Narratives
1.  **The 2008 Financial Crisis**: How the Euro-Dollar rate reacted during the global market collapse.
2.  **The Three Eras**: Comparing the Euro's performance under different US Presidential terms (Bush, Obama, Trump).
3.  **The COVID-19 Impact**: Initial market reaction to the 2020 pandemic lockdowns.

---

## 📝 Conclusion & Key Takeaways

We have transformed raw exchange rate data into a clean, professional, multi-panel data story. By applying the **30-day rolling mean**, maximizing the **data-ink ratio**, and using distinct colors, we can draw clear economic conclusions from our visualization:

### 1. The George W. Bush Era (2001–2009): Strategic Decline of the Dollar
* **Trend**: The Euro started weak (around 0.90 USD) but grew consistently stronger, peaking at its historical maximum of nearly **1.60 USD** in 2008.
* **Context**: This period was heavily impacted by the war in Iraq, rising US budget deficits, and ultimately, the crash of the US housing market which led to the **2008 Global Financial Crisis**. Investors temporarily lost confidence in the Dollar, driving the Euro up.

### 2. The Barack Obama Era (2009–2017): Stability and European Crisis
* **Trend**: The Euro remained relatively high at first (around 1.40 USD) but experienced a steady downward trend, dropping to around 1.10 USD by the end of his term.
* **Context**: While the US economy was slowly recovering from the recession, Europe was hit by the **European Debt Crisis** (problems in Greece, Italy, and Spain). This weakened the Euro significantly against a recovering US Dollar.

### 3. The Donald Trump Era (2017–2021): Volatility and Trade Tension
* **Trend**: The Euro fluctuated between 1.10 USD and 1.25 USD, showing clear cycles of ups and downs without a single long-term direction.
* **Context**: This period was marked by global trade tensions and policy uncertainty. The sudden rise at the end of 2020 reflects the global market reaction to the **COVID-19 pandemic**, where international markets experienced rapid shifts.

---

### 💡 Data Science Skills Demonstrated in this Project:
* **Data Prep**: Cleaned real-world datetime and string-to-float anomalies.
* **Signal Engineering**: Implemented Rolling Means to remove daily noise.
* **Information Design**: Built a custom $2 \times 3$ grid using `Matplotlib` and aligned formatting rules inspired by *FiveThirtyEight* journalism.
