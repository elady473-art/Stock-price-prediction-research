# Stock-price-prediction-research
A GAN-Enhanced Deep Learning Framework for Improving Stock Price Prediction Accuracy Using NASDAQ Financial Time-Series Data
Abstract
Stock price prediction is highly challenging due to volatility, noise, and nonlinear patterns in financial markets. Traditional statistical models and even advanced deep learning models like LSTM often fail under unstable market conditions. This study proposes a hybrid GAN-LSTM framework where Generative Adversarial Networks (GANs) generate synthetic financial time-series data to enhance training. The augmented dataset is then used to train an LSTM model for improved short-term prediction accuracy. The model is evaluated using MAE, RMSE, and R², and compared against ARIMA and standard LSTM baselines.
Tools & Technologies
Python
PyTorch
Google Colab
NumPy, Pandas, Scikit-learn
Matplotlib
 Dataset
NASDAQ stock data (2015–2025)
Features: Open, High, Low, Close, Volume (OHLCV)
Source: Kaggle / UCI / IEEE DataPort
 How to Run
Clone repository: git clone https://github.com/elady-art/gan-lstm-stock-prediction
Install dependencies: pip install -r requirements.txt
Run the model: python main.py
 Expected Outcome
The proposed GAN-LSTM model is expected to reduce RMSE by 10–15% and improve prediction stability in volatile NASDAQ markets.
 Author
Emebet Mesfin
Hawassa University – Computer Science
