# Market regime detection using Statistical and ML based approaches

## <a id="overview"></a>Overview
Financial markets microstructure behaviour can vary over time, being affected by a wide range of external and internal factors. This can result in different market regimes or periods of continuous similar market conditions. Financial market participants aim to detect these market regimes and their shifts to handle potential risks and make better-informed investment decisions. 

Different approaches exist allowing the classification of market regimes. Many practitioners or researchers categorise markets as "boom" or "bust" markets, while others categorise them based on volatility, such as high, low, and mid-volatility regimes. Another approach is to classify market conditions into "risk on" or "risk off" states based on the investors' appetite. 

Identification of market regimes is an unsupervised process, and there is a wide range of techniques that can help to determine the current market state based on historical market data. These techniques include statistical approaches, such as vector autoregression models and hidden Markov models, as well as machine learning approaches, like clustering models e.g., k-means, agglomerative clustering, and gaussian mixture models. 

In the scope of this blueprint article, we aim to identify normal (growth) or crash (rapid decline) market states for S&P 500 using several statistical and ML models, including gaussian HMM, k-means clustering, and gaussian mixture models. Additionally, we build a simple investment strategy based on the identified market states and compare that with the base "Buy and Hold" strategy of the same asset throughout the analysis period. 

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Data Libraries license that has API access 
- Tested with Python 3.7 and 3.9
- Packages: see inside the notebook
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan, Jason Ramchandani, Marios Skevofylakas**
