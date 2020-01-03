# Law and Governance of AI

## Project Description
This project is for the class **Law and Governance of Artificial Intelligence** at [Northwestern University](www.northwestern.edu).

### Problem
The U.S. Stock market is the largest financial market in the world and there is an increasing need to protect it from malicious activities, such as insider trading. Insiders are informed market participants that must trade according to strict regulations in the company for which they possess material non-public information. Most people consider "insider trading" risky — traders exploiting insider knowledge for their own gain.

Insiders' trading abilities are regulated through several methods: (i) scheduled transactions at recurring frequencies, or (ii) open market transactions.

Scheduled transactions allow for insiders to buy/sell shares in a consistent manner. A pre-arranged consistent schedule reduces the risk of having material information informing their decision.

Insiders must be careful to ensure they aren't using material information to inform their decision — a big undisclosed contract, a new drug discovery, etc. are all information that the market hasn't had an opportunity to process, and as such, prohibited by insiders to act on. Insiders do, however, possess information about the general pulse of the company and therefore, these transactions contain general sentiments about the company.

### Goal
As the business activities become ever more complicated today, from the public sector to the private one, from the [U.S. Securities and Exchange Commission (SEC)](https://www.sec.gov/) to the compliance group led by a general counsel in a company, fast and reliable monitoring tools are in ever high demand — to efficiently detect suspicious activities in financial markets, in particular the U.S. stock market.

### Result
We built several methods to detect abnormal transction patterns, including the 8 patterns proposed in the paper below. The data we used are from [Yahoo Finance](https://finance.yahoo.com/). As for the future work, we plan to incorporate other features such as organization’s ranking on the news/[Twitter](www.twitter.com) etc. This would help us to corroborate any red flags we raise using our unsupervised techniques.

#### Directory Structure:
     .
     ├── pattern_identification 1.0         # elementary analysis on trading volume and transactions (by Mayank)
     ├── pattern_identification 2.0         # implemnetation of 8 pattern detection techniques mentioned in the reference paper (by Albert)
     ├── .gitignore                         # contains file types not to be synced with GitHub                     
     └── README.md

### Further Reference
- [Foundations of Technical Analysis - Computational Algorithms, Statistical Inference, and Empirical Implementation](https://onlinelibrary.wiley.com/doi/full/10.1111/0022-1082.00265)
- [For the First Time, Nasdaq Is Using Artificial Intelligence to Surveil U.S. Stock Market](https://www.nasdaq.com/articles/for-the-first-time-nasdaq-is-using-artificial-intelligence-to-surveil-u.s.-stock-market)
- [FactSet Ownership - Aggregated Insider Transactions](https://www.quantopian.com/docs/data-reference/ownership_aggregated_insider_transactions#definition-of-an-insider)

### Team Members:
- Albert Guo [@Albert-Z-Guo](https://github.com/Albert-Z-Guo)
- Mayank Malik [@mayankmalik01](https://github.com/mayankmalik01)
- Jack Richard [@Richarjw](https://github.com/Richarjw)