# Crypto_Arbitrage_Analyzer

![An image illustrating arbitrage.](https://img.currency.com/articles/-INFOGRAPHIC-Arbitrage-crypto-explained-Q-A.png)

---
## The Analyzer

The Crypto Arbitrage Analyzer is a Python-based Jupyter Notebook that sorts through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. This analysis considers arbitrage opportunities using closing prices between the two exchanges during a three month period in 2018.

---
## Technologies
This analyzer was created on Python 3.7 with [Jupyter Lab](https://jupyter.org/install) and uses the [Pandas](https://pandas.pydata.org/) and [pathlib](https://docs.python.org/3/library/pathlib.html) libraries.

---
## Installation Guide
The dependencies needed to use the anaylzer are:

```python
import pandas as pd
from pathlib import Path
import numpy as np
%matplotlib inline
```

---
## Usage
Launch Jupyter Lab and run the program 
```python
crypto_arbitrage.ipynb
```
Once the data has been collected and read-in by running the cells, the program will start displaying plots representing different pieces of data that look like this:
* Bitcoin's Closing Price January 28th, 2018 - Bitstamp v. Coinbase:
![A screenshot of Bitcoin's closing prices in January 2018](https://user-images.githubusercontent.com/89755088/137576906-e77e8edb-75ab-49e6-994e-33e2277dab7f.png)
* The arbitrage spread for January 28th, 2018 - Bitstamp v. Coinbase:
![A screenshot representing Bitcoins arbitrage spread again Bitstamp and Coinbase](https://user-images.githubusercontent.com/89755088/137576948-b64503c0-b54c-4202-ac57-9340d3ae71ea.png)
* Bitcoin's Cumulative profits for January 28th, 2018:
![A screenshot representing Bitcoins cumulative profits for January 28th](https://user-images.githubusercontent.com/89755088/137577102-d7dc47f3-a902-4bbc-b940-49699e11d735.png)

---
## Analysis Findings
This analysis identified substantial arbitrage opportunities in the months of January and February where Bitcoin was selling lower on Bitstamp than on Coinbase. It also revealed that the arbitrage opportunities disappeared in the month of March.

---
## Contributors

This starter code was created from © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand. 

Additional code was added for full analysis by Thomas Leahy, thomasleahy6@gmail.com

---
## License

MIT Licence

2021 Thomas Leahy