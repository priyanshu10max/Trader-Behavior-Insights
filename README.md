# Trader-Behavior-Insights-Analysis

🧠 Objective:-

* To analyze how market sentiment (Fear & Greed Index) affects trader behavior and profitability. The project combines historical trading data with sentiment indicators to extract actionable insights and recommend smarter trading strategies.

📊 Datasets Used:-

(1) Bitcoin Market Sentiment (Fear & Greed Index):-

* Fields: timestamp, value (0–100), classification (Fear, Greed, Neutral), date

(2) Historical Trader Data:-

* Fields: Account, Coin, Execution Price, Size Tokens, Size USD, Side, Date, Start Position, Direction, Closed PnL, Transaction Hash, Order ID, Crossed, Fee, Trade ID, Timestamp

🧱 Tech Stack

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

* Jupyter Notebooks

* Data Merging

* Clustering & Classification Models

📌Key Insights:-

* Traders tend to buy more during Greed and sell more during Fear.

* Losses are higher during fearful sentiment periods.

* Certain trader clusters are consistently profitable regardless of sentiment, indicating the presence of experienced traders.

* High market sentiment value does not always correlate with high PnL, suggesting overconfidence during greedy times.
