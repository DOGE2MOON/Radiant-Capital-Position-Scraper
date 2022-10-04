# Radiant-Capital-Position-Scraper

Gathers on-chain user-level data from Radiant.capital using web3 calls in Python. Uses CoinGeckoAPI to gather token prices for the purpose of calculations. Can be modified to work with other lending markets with token rewards such as Geist.finance, Valas.finance, and the eventual Radiant BSC deployment. 

# Example Usage
get_RDNT_data("YOUR_ADDRESS_HERE")

(to CSV)
get_RDNT_data("YOUR_ADDRESS_HERE").to_csv("filename.csv", encoding = 'utf-8')
