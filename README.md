# Introduction
The primary goal of this repository is to download Bitcoin transaction files from Bitget. Since these files are only available for individual download, we use Selenium to automate the process of interacting with the website and downloading the files. The aim is to collect comprehensive transaction data for analysis.

## Project Overview
The **Bitget Transaction Downloader** automates the download of Bitcoin transaction files from Bitget; a major cryptocurrency exchange with historical data from 2018 to 2024, using Selenium. The automation script mimics user interactions to handle the bulk download of datasets for each year from 2021 to 2024.

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
Downloader can be found under the `notebooks` folder. For better management, we recommend using Jupyter Notebooks to run it.

># Note
>1. **The primary goal of this project is to automate the download of Bitcoin transaction files. The collected data will not be processed within this project.**
>2. **The files are downloaded as-is, and it is the user’s responsibility to manage and organize their own data. However, the final full dataset is available here: [Bitcoin Transactions History (2021 - 2024)](https://www.kaggle.com/datasets/imadallal/bitcoin-transactions-history-2021-2024).**
>3. **This final full dataset (referenced above) will be processed and extracted into a *hourly price dataset*  in the project here: [Bitcoin-Dataset-Viewer-and-Preparer](https://github.com/Bitcoin-Price-Prediction-Experiments/Bitcoin-Dataset-Viewer-and-Preparer)**

