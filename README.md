# Stock-Market-Analyser


![Stock Market Analyzer](images/stock_analyzer.png)

The Stock Market Analyzer is a project that uses Long Short-Term Memory (LSTM) neural networks to analyze and predict stock prices. This repository contains the code and resources needed to train and utilize the LSTM model for stock market analysis.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Data Collection](#data-collection)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training](#model-training)
  - [Prediction](#prediction)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Stock market analysis and prediction have always been challenging tasks due to the volatile and complex nature of financial markets. This project aims to provide a tool for analyzing historical stock price data and making short-term predictions using LSTM, a type of recurrent neural network well-suited for sequential data.

The project involves data collection, preprocessing, model training, and prediction phases. The LSTM model learns patterns from historical stock prices and attempts to predict future price movements.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (>= 3.6)
- Git

### Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/stock-market-analyzer.git
cd stock-market-analyzer
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

### Data Collection

To collect stock market data, I used various data source Yahoo Financel APIs. Update the data collection script (`collect_data.py`) with the desired stock symbols, date range, and data source.



### Data Preprocessing

Data preprocessing is crucial for preparing the collected data for training the LSTM model. to clean, normalize, and transform the data.


### Model Training

Train the LSTM model using the preprocessed data. The architecture and hyperparameters of the model can be configured in the `train_model.py` script.
visit keras_model.h5,LSTM model.ipynb


### Prediction

Use the trained LSTM model to make predictions on unseen data. Update the `predict.py` script with the necessary inputs and run it.

```bash
app.py 
```
run it in terminal using "Streamlit run app.py"
## Results
![1 1](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/ef1b5f8f-cd4a-4ce9-ac36-c97c57fc3161)
![2 2](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/09fae5f2-ec15-4ae5-8b1a-ed08340009e5)
![3 3](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/e0c240d5-b308-4fa3-ad21-2cf76bd22907)
![4 4](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/b8acb6cb-303d-483f-bdd6-d0ccf7a734ef)
![5 5](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/0b06c9f6-8133-47c4-bbee-b9142e3a33b1)




## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, please create a pull request or open an issue in this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Disclaimer**: Stock market prediction is inherently uncertain and comes with risks. The predictions made by this model should not be used as the sole basis for financial decisions. Always consult with financial professionals before making investment choices.
