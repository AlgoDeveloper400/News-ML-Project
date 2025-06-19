# 📰 News-ML-Project

This project showcases a Recurrent Neural Network (RNN) trained on economic news data extracted from the MLQ5 website using a custom Python script.

# 🔍 Project Overview
The dataset was built using Python by interacting with web elements on the MLQ5 calendar page. The script scrapes both table data and paginated content (using the "Next Week" button) to collect multiple weeks of news events.

Due to the simplicity and reproducibility of the web scraping process, only partial code snippets will be provided in this repo.

# ⚙️ Background
Previously, I attempted to collect news data directly within MetaTrader 5 (MT5) using MQL5. However, this was extremely tedious due to the lack of accessible historical news data in the MT5 strategy tester. To overcome this limitation, I developed a custom MQL5 framework with include files for class/function storage to simulate historical news events during backtests. While it worked, it was very slow and technical (heavy C++), and not the main focus of this repository. I plan to release that framework in a separate, dedicated repo later.

# 🧠 Machine Learning Focus
This project’s main objective is to leverage the extracted news data for machine learning, specifically by applying Recurrent Neural Networks (RNNs) like LSTMs or GRUs, which are well-suited for time-series forecasting and sequential data.
📄 [Read the Disclaimer](Disclaimer.md)

# 📆 Data Used
The data collected spans from January 2007 through June 2025, covering approximately 18 years of news data. Although this sounds like a lot, many economic news events typically occur only once or twice per month, so the total number of events is relatively limited.

For the sake of demonstration, this repository includes only this year's news data. If you need data covering a longer period, you'll need to build your own script to collect it. Fortunately, creating such a data collection script is not very difficult. 

