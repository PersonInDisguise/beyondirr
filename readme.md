# AMLR Strategy Evaluation

## Overview

This repository contains the codebase for the AMLR strategy, including its core development and subsequent out-of-sample performance testing.

To maintain strict evaluation standards and prevent data leakage, the historical analysis and the forward-testing have been separated into two distinct files based on their respective timeframes.

## Repository Structure \& Data Periods

* **`2651\\\_AMLR\\\_strategy\\\_final\\\_QuantFinChallenge`**

  * **Timeframe:** 2010 – 2020
  * **Purpose:** This file contains the primary codebase for the strategy's logic, model training, and initial backtesting across the 2010-2020 dataset.
* **`2651\\\_2020\\\_2025\\\_testing\\\_QuantFinChallenge`**

  * **Timeframe:** 2020 – 2025
  * **Purpose:** This file is strictly dedicated to the out-of-sample testing and validation of the finalized strategy using the more recent 2020-2025 market data.

## How to Run

1. Review or execute `2651\\\_AMLR\\\_strategy\\\_final\\\_QuantFinChallenge` to understand the core algorithm and view the baseline backtest results for the 2010-2020 period.
2. Execute `2651\\\_2020\\\_2025\\\_testing\\\_QuantFinChallenge` to run the strategy against the unseen 2020-2025 dataset and evaluate its recent performance.
3. Here we use the 2010-2020 data as the training data and execute results for the 2020-2025 dataset.



