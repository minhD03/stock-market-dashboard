# Stock Market Dashboard: [Live Report](https://app.fabric.microsoft.com/view?r=eyJrIjoiMjA3MDJiMTYtMWM2OS00YmEwLTk4OTQtZGM5YmFmMTRjMmI5IiwidCI6IjZhNjhlMmQxLWQ4OGQtNDEyYi1iOTgyLWQ0YWVkNWY1MTcxNiJ9)
## 1) Overview:
This dashboard is the continuous of the [Stock Market project](https://github.com/minhD03/stock-market.git), using the datasets collected from the project. 

Problem Statement: Investors and analysts need an efficient way to compare the performance, risk, and trading behavior of multiple technology stocks over time. While stock prices alone provide limited insight, investment decisions require evaluating returns, volatility, drawdowns, and market activity simultaneously.
To solve the problem, this dashboard aims to answer the following business questions while tracking the top 10 most popular technology company (Apple, Microsoft, Google, Amazon, Tesla, Meta, Netflix, Nvidia, AMD, Intel):

- Which technology company generated the highest return during the analysis period?
- Which stocks exhibited the highest and lowest volatility?
- Is higher return associated with higher investment risk?
- Which companies experienced the largest drawdowns during market downturns?
- Which stocks provide the most attractive balance between risk and return?
- Which companies demonstrate the strongest recent momentum based on price performance?

## 2) Dataset:
The dataset contains daily stock market information including:
- Timestamp.
- Date
- High Price.
- Low Price.
- Open Price.
- Close Price.
- Trading Volume.
  
## 3) Screenshots:
![alt text](https://github.com/minhD03/stock-market-dashboard/blob/8ed80b2bfc022ce575488ad24eb03e93616293fe/images/dashboard-1.png)
![alt text](https://github.com/minhD03/stock-market-dashboard/blob/8ed80b2bfc022ce575488ad24eb03e93616293fe/images/dashboard-2.png)

## 4) Key Measures:
### a) Total Return (%)
Measure the investment growth from the first trading day count to the latest available date based on Close Price.
### b) Volatility: 
Indicate the stability of a company by measuring how fast and how much stock price moves up and down over time.
### c) Dragdown:
Demonstrate the most declined that each company underwent from the past.

## 5) Key findings:

- From 2022 to present, NVIDIA showed the highest return with 10,68 times higher, followed by the highest volume and high volatility rate (0.04).
- However, from the last year (23/06/2025), the first place had been replaced by Intel (5.24), followed by AMD (3.04). 
- Meanwhile, although increasing remarkably with 2.82 times, Netflix has shown a small decrease by -0.42, which is the lowest return from 23/06/2025.
- From 2024, Apple had reached the top stock price among the 10 companies.
- Surprisingly, while Apple withnessed a slight decrease in stock price recently, AMD had surged up to catch up with Apple.
- Over the period, AMD, Intel and Tesla had the largest declined by approximately 0.64.
- On the other hand, Google and Apple were the most endurance companies with around 0.32.
- Noticably, along with the reduce of total return, Netflix also took the biggest fall with -0.46.
- In addition, Nvidia and Apple had overcame Google with nearly 0.14 and 0.2.
- From 23/05/2025 until present, Intel had surpassed Nvidia in both total return and volatility (0.05), followed by AMD (0.04). However, most of the companies were keeping their volatility below 0.03 and return below 2. But, Nvidia still stays with the highest trading volume.

## 6) Conclusions:
In conclusion, from last year (23/05/2025), Intel and AMD were the highest total return and volatility. Meanwhile, Netflix and Microsft were struggled as their volatility were low and total return were negative. It can be seen that all the companies were either in aggressive growth (Intel, AMD) or defensive (Apple, Nvidia, Google). Furthermore, some were even encountered difficulties in maintaining their stock price (Microsoft, Netflix), with Netflix had undergone the worst dropdown. As a result, with increasing price and even catch up with Apple, not only does AMD showed the most attractive balance between risk and return, but it also illustrated the strongest momentum based on price performance. A major factor behind these patterns is the broader technology sector cycle driven by AI adoption, interest rate changes, and semiconductor demand shifts between 2022–2025. Companies such as NVIDIA and AMD benefited strongly from the rapid expansion of AI infrastructure demand, where GPUs and high-performance computing became critical, leading to sustained upward price momentum and higher volatility. In contrast, more mature growth companies like Microsoft experienced periods of consolidation as markets reassessed valuations amid higher interest rates, despite strong fundamentals in cloud and AI services (Azure). Meanwhile, Netflix faced structural changes in its growth model, including the introduction of ad-supported plans and intensified competition in the streaming industry, which contributed to more mixed sentiment and weaker relative momentum compared to high-growth AI-driven peers.
