# Tweet Extraction

This repository contains the dataset and Jupyter Notebook used for extracting tweets and analyzing them alongside financial fact-checks. 

## Repository Structure

The project directory contains the following core files:

* **`tweetextract.ipynb`**: The primary Jupyter Notebook containing the logic and code for the extraction process.
* **`raw_tweets_bulk.json`**: A JSON file containing the bulk export of raw, scraped tweet data.
* **`pib_financial_factchecks_final.csv`**: A final CSV dataset comprising financial fact-checks from the Press Information Bureau (PIB).

## Data Overview

* **Raw Tweets**: `raw_tweets_bulk.json` serves as the primary unstructured data source.
* **Fact-check Data**: `pib_financial_factchecks_final.csv` is used as the structured reference dataset for verifying or cross-referencing financial claims.

## Usage

1. Clone or download the repository to your local machine.
2. Open `tweetextract.ipynb` in your preferred Jupyter environment.
3. Ensure your Python environment is set up to handle `.csv` and `.json` data ingestion before running the notebook cells.
