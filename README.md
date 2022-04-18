# Challenge-3

The Directory for this respoitory is:
[Summary](https://github.com/mimisull/Challenge-3/blob/main/README.md)
[Code](https://github.com/mimisull/Challenge-3/blob/main/crypto_arbitrage.ipynb)
**Challenge Arbitrage Opportunity for Bitcoin**
> Specifically, BizOps wants to know if this software can prompt the user to save the qualifying loans as a new CSV file.
*User Story*:
As a user, I need the ability to compare data from Coinbase and from Bitstamp and find where their are price differences so that I can make profitable trades without sorting manually through spreadsheets.

*Acceptance Criteria*:
Given that I’m unable to effectively sort through all this data manually on excel, the tool I build should be able to collect, clean, and analyze the data with visuals.


## Usage
The project works by cleaning the data, importing the CSV files, and comparing prices listed by timestamp.
Collected the data via this code:
'''coinbase = pd.read_csv(
    Path("./Resources/coinbase.csv"),
    index_col="Timestamp",
    parse_dates=True,
    infer_datetime_format=True)'''

## Contributors
Michael Sullivan

Cal Berkeley Fintech 

Kevin Lee
