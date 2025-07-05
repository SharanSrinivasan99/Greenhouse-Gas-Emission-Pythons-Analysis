# 🌱 Greenhouse Gas Emissions Analysis

Ever wondered how much methane your country's cows are producing? We did,and it led us to this emissions-wrangling deep dive. This project combines climate and economic data from **OECD, World Bank, and IMF** to explore what’s heating up our planet (hint: it’s not just your car).

---

## 🧠 Project Summary

In this group project, we:
- Cleaned and merged climate datasets across organisations (OECD + WB + IMF)
- Used Python to wrangle it all into one tidy dataset
- Built some sweet visualisations in Python
- Answered 3 real-world questions a policy analyst might ask
- Proposed a web scraping solution to fill in the gaps 

---

## 🛠 Tools & Tech Stack

- Python (pandas, requests, BeautifulSoup)
- Jupyter Notebook
- Web scraping (lightweight, proof-of-concept)
- Datasets from [OECD](https://data.oecd.org), [World Bank](https://data.worldbank.org), [IMF](https://www.imf.org)

---

## 📊 Data at a Glance

We merged multiple sources into one final dataset featuring:
- Emissions by gas type and sector (CO₂, CH₄, N₂O and friends)
- Methane contributions by country and sector (agriculture, waste, etc.)
- Environmental protection spending (% of GDP)

> Final result: a lean, clean, insight-generating machine (aka a CSV)

---

### ✅ Three Key Questions We Answered

1. **What are the dominant components of GHG emissions and their primary sources across countries?**  
   → CO₂ accounts for 83.2% of emissions globally; methane (CH₄) dominates in agriculture-heavy nations.

2. **What is the current state of methane emissions in New Zealand?**  
   → CH₄ is 47.5% of NZ’s total GHG output, with **83.4%** of it coming from the **agriculture sector**.

3. **What’s the trend of NZ’s environmental expenditure, and has it been effective in controlling emissions?**  
   → Spending peaked in 2014–2017 and correlated with a sharp drop in emissions. But post-2017? Not so great — emissions spiked again.

---

## 💡 Key Insights

- **CO₂ remains the global heavyweight**, but **methane** is a serious contender in agricultural economies like NZ.
- **Spending works — until it doesn’t.** NZ’s environmental expenditure showed promising impact when consistent, but declines in funding coincided with emission rebounds.
- **New Zealand’s methane problem is sector-driven**, not seasonal. 



---

## ⚠️ But We Hit a Wall...

We wanted to know:
> **What policies has NZ implemented to reduce emissions, and have they worked?**

Sadly, our dataset didn’t know. It’s just numbers — no politics.

---

## 🕵️ Web Scraping to the Rescue

To answer the policy question, we proposed scraping:
- Government sites like [legislation.govt.nz](https://www.legislation.govt.nz)
- News articles (e.g., BBC, Stuff, NZ Herald)
- Ministry for the Environment updates

We even tested it out with a mini crawler to pull sample policy headlines and snippets. It’s not great, but it does the job.

---

📌 Disclaimer

This project was developed for academic purposes only. All data sources are public. No cows were harmed during analysis (but they were blamed a little).

