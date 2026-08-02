# LLM Prompt Performance & Token Analytics

An analytical project focused on evaluating Large Language Model (LLM) performance, response latency, token consumption, and cost efficiency. Built as part of the Global Certification Course (GCC) - Gen AI Track.

## 📌 Project Overview
This project sets up an in-memory SQL database (`promptlogs`) in Google Colab to log and analyze execution metrics from various Generative AI models (`gpt-4o`, `gpt-4o-mini`, `claude-3-5-sonnet`).

## 📊 Key Findings & Insights
- **Cost & Latency Efficiency:** `gpt-4o-mini` emerged as the fastest (446.67 ms avg latency) and most cost-effective ($0.0006 total cost) model.
- **Output Quality:** `claude-3-5-sonnet` achieved the highest user feedback score (4.33/5.00) with balanced latency.
- **Performance Bottlenecks:** Identified high-token prompts causing significant response delay (e.g., Log ID 107 peaked at 4800 ms for 2950 tokens).

## 🛠 Tech Stack
- **Language:** Python
- **Database:** SQLite
- **Data Manipulation:** Pandas
- **Visualization:** Matplotlib
- **Environment:** Google Colab

## 🚀 How to Run
1. Open `LLM_Prompt_Performance_and_Token_Analytics.ipynb` in Google Colab.
2. Run all cells sequentially (`Ctrl + F9`).
3. View the generated SQL query tables and Matplotlib visualization plots.
