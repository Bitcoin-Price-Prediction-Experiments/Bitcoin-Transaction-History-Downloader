# Introduction
The primary goal of this repository is to download Bitcoin transaction files from Bitget. Since these files are only available for individual download, we use Selenium to automate the process of interacting with the website and downloading the files. The aim is to collect comprehensive transaction data for analysis.

## Project Overview
- **Bitget Transaction Downloader:** Automates the download of Bitcoin transaction files from Bitget, a major cryptocurrency exchange with historical data from 2018 to 2024. The automation script mimics user interactions to handle the bulk download of datasets for each year from 2021 to 2024.

<br>

# Getting Started

To set up the project, follow these steps:

## Clone the Repository

   ```bash
   git clone https://github.com/Imad-Allal/Bitcoin-Transaction-History-Downloader
   cd Bitcoin-Transaction-History-Downloader
   ```

## Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

## Usage
Downloader can be found under the `notebooks` folder. For better management, we recommend using Jupyter Notebooks to run them.

<br>

# Note
1. **The primary goal of this project is to automate the download of Bitcoin transaction files. The data will not be stored in a database or any other form of persistent storage. Files are downloaded as-is, and it is the user’s responsibility to manage and organize their own data.**
2. **The final dataset is available here: [Bitcoin Transactions History (2021 - 2024)](https://www.kaggle.com/datasets/imadallal/bitcoin-transactions-history-2021-2024)**

