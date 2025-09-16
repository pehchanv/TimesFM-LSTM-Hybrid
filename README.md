# TimesFM-LSTM-Hybrid

This project explores a **hybrid forecasting approach** by combining **Google's TimeSFM model** with a **Long Short-Term Memory (LSTM) network**. The goal is to improve predictive accuracy for financial time series data, specifically stock prices.

## Project Overview
- Integrates **transformer-based TimeSFM** with **recurrent LSTM layers**.  
- Developed and tested in **Google Colab**.  
- Focuses on capturing both long-term dependencies and local sequential patterns in financial datasets.  

## Code
The main implementation is provided in the repository.

## How to Use
1. Open the notebook in Google Colab.  
2. Run the setup cells to install dependencies.  
3. Upload or connect your dataset (e.g., NIFTY 100 stock prices).  
4. Execute the training and evaluation cells.  

## Repository Structure
- `TimesFM_LSTM_Hybrid.ipynb` → Main implementation.  
- `README.md` → Project description (this file).  

## Results (Planned)
- Forecasting accuracy comparison between baseline LSTM, TimeSFM, and the hybrid model.  
- Visualization of predicted vs actual stock price movements.  

## Future Work
- Package hybrid architecture into standalone Python scripts.  
- Extend experiments to other financial indices and asset classes.  
- Automate hyperparameter tuning for improved performance.  

✍️ *Maintained by [Pehchan](https://github.com/pehchanv)*  
