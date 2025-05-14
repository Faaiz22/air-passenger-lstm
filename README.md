# Air Passenger Forecasting using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to perform time series forecasting on the classic **Air Passengers dataset**, which contains monthly totals of international airline passengers from 1949 to 1960.

## 📁 Files Included

- `AirPassenger_LSTM.ipynb`: The Jupyter Notebook with all code, explanations, and plots
- `AirPassengers.csv`: The original dataset used for training and testing

## 📈 Objective

The main goal is to predict future airline passenger counts using deep learning. I used LSTM, a type of recurrent neural network (RNN), because it's well-suited for sequential data like time series.

## 🔧 Tools & Libraries Used

- Python (in Google Colab)
- TensorFlow / Keras
- Pandas
- Matplotlib
- scikit-learn (for normalization)

## 🧠 Model Summary

- Used past 12 months (1 year) of data to predict the next month's passenger count
- The dataset was split into 80% training and 20% testing
- Data was normalized using MinMaxScaler
- Trained an LSTM model with early stopping to avoid overfitting

## 📊 Results

The model performed well in capturing the trend of passenger growth over time. A final plot comparing actual vs. predicted values on the test set shows close alignment.

## 🧪 Future Scope

- Predict values beyond 1960 (future forecasting)
- Try other models like ARIMA or Prophet for comparison
- Hyperparameter tuning for even better performance

## 💡 What I Learned

- How to prepare time series data for LSTM
- Normalization and reshaping techniques
- LSTM architecture and training
- Visualizing performance and interpreting results

---

📌 **Note**: This project was done as part of a coursework submission.  
Feel free to explore or reuse the notebook for learning purposes!

