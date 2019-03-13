# Nasdaq-ITCH-5.0-VWAP
This project parses the NASDAQ ITCH 5.0 data and output the volume-weighted average price (VWAP) for each stock at every trading hour.

Please make sure users have installed Python2 with the packages `gzip`, `struct`, `datetime`, `os`, and `pandas`.

# Run Code

Navigate to the src directory and run the following commands in the terminal.

`python2 parser.py`

# Dataset

Download raw ITCH 5.0 data from `ftp://emi.nasdaq.com/ITCH/01302018.NASDAQ_ITCH50.gz`. Copy it into `res` folder.

The data format is defined by the document [Nasdaq TotalView-ITCH 5.0.](http://www.nasdaqtrader.com/content/technicalsupport/specifications/dataproducts/NQTVITCHspecification.pdf)
