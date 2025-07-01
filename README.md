# 📰 News-ML-Project

This project showcases a Recurrent Neural Network (RNN) trained on economic news data extracted from the MT5 platfom using an advanced data collection script.

# 🔍 Project Overview
The dataset was built using a custom MQL5 data collection script, which uses include files, expert advisors and binary files to collect, process and store the data.

# ⚙️ Background
I developed a custom MQL5 framework with include files for class/function storage to simulate historical news events during backtests. While it worked, it was very slow and technical (heavy C++). I have compared it with the other Python data script that I made and the data is very similar, missing data here and there but the overall structure is relatively the same. I will release this other version in another repository.

# 🧠 Machine Learning Focus
This project’s main objective is to leverage the extracted news data for machine learning, specifically by applying Recurrent Neural Networks (RNNs) like LSTMs or GRUs, which are well-suited for time-series forecasting and sequential data.
📄 [Read the Disclaimer](Disclaimer.md)

# 📆 Data Used
The data collected spans from January 2007 through June 2025, covering approximately 18 years of news data. Although this sounds like a lot, many economic news events typically occur only once or twice per month, so the total number of events is relatively limited.

For the sake of demonstration, this repository includes only this year's news data. If you need data covering a longer period, you'll need to build your own script to collect it. Unfortunately creating such a script is very tedious and requires a great deal of how the economic calendar works in the MT5 platform, I will leave some documentation on how you can build yours.

# 🗞️ Economic News Event Counts by Currency and Impact
This CSV file contains counts of how many times each unique economic news event occurred for each currency, grouped by impact level, based on cleaned data from 2007 to 2025. The data supports filtering by impact type and includes clear header lines separating each currency’s events for easy analysis.

Note: Having less data, especially for rare or missing events, can negatively affect the performance of Recurrent Neural Networks (RNNs) trained on this dataset. Sparse or incomplete event histories reduce the model’s ability to learn meaningful temporal patterns, which can lead to less accurate predictions. Some events are holidays so they will not be used in the calculations, all of which have impact type 0.



