# Market Basket Analysis

This repository contains my BIL 476 Data Mining course project. It uses the Online Retail II dataset to compare Apriori and FP-Growth and to examine association rules from retail transactions.

The rules are evaluated using support, confidence, lift, Kulczynski, cosine, and imbalance ratio. The full analysis is in `BIL476_Market_Basket_A100_Optimized.ipynb`.

- `data/`: raw and processed data
- `results/`: exported tables and rule outputs
- `figures/`: plots used in the analysis

The notebook was prepared for Google Colab. Run the cells in order. The Apriori tests at lower support values use a large amount of RAM, so a high-memory runtime may be needed.
