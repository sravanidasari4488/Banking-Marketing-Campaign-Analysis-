# 🏦 Portuguese Bank — Term Deposit Marketing Campaign Analysis

A data science case project analysing a real-world telemarketing dataset from a Portuguese bank to uncover what drives customers to subscribe to term deposits.

---

## 📁 Project Structure

```
├── banking_analysis.ipynb          # Main analysis notebook (code + outputs)
├── banking_campaign_presentation.pptx  # Summary PowerPoint presentation
└── README.md
```

---

## 📊 Dataset Overview

| Attribute | Detail |
|-----------|--------|
| Source | Portuguese Bank Direct Marketing Campaign |
| Period | May 2008 – November 2010 |
| Records | 45,216 client contacts |
| Target Variable | `y` — Did the client subscribe to a term deposit? (yes/no) |
| Subscription Rate | 11.7% (significant class imbalance) |

The dataset contains **17 features** across three categories:

- **Client demographics** — age, job, marital status, education, credit default, account balance, housing loan, personal loan
- **Campaign contact details** — contact type, last contact day & month, call duration, number of contacts
- **Previous campaign history** — days since last contact, prior contacts, previous outcome

---

## 🔍 Questions Answered

1. Distribution of client age
2. Job type variation among clients
3. Marital status distribution
4. Education level breakdown
5. Proportion of clients with credit in default
6. Distribution of average yearly balance
7. How many clients have housing loans?
8. How many clients have personal loans?
9. Communication types used for contact
10. Distribution of last contact day
11. Last contact month variation
12. Distribution of call duration
13. Number of contacts during campaign
14. Days since previous campaign contact (pdays)
15. Number of contacts before current campaign
16. Previous campaign outcomes
17. Subscribed vs. not subscribed distribution
18. Correlations between attributes and subscription likelihood

---

## 💡 Key Findings

| Finding | Insight |
|---------|---------|
| **Call Duration** | Strongest predictor (r = 0.394) — subscribers averaged 537s vs 221s |
| **Previous Success** | Clients who subscribed before convert at **64.8%** |
| **Best Segments** | Students (28.7%) and Retirees (22.9%) have the highest conversion rates |
| **Best Months** | March, September, October, December yield 35–51% conversion |
| **Loan Holders** | Housing loan holders convert at only 7.7% vs 16.7% without |
| **Contact Channel** | Cellular (14.9%) far outperforms unknown channel (4.1%) |
| **Excessive Calling** | More than 3 calls per client negatively impacts conversion |

---

## 🛠️ Tech Stack

- **Python 3** — pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook** — analysis and code transcript
- **PowerPoint** — executive summary presentation

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/banking-campaign-analysis.git
cd banking-campaign-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook banking_analysis.ipynb
```

> **Note:** Place `banking_data.csv` in the path `DsResearch/DsResearch/Banking/banking_data.csv` before running, or update the file path in the first code cell.

---


---

*Case Project — Banking Industry | Data Science Programme*
