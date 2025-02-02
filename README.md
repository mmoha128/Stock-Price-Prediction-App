# Stock-Price-Prediction-App

# Description:
### **Stock Price Prediction App 📈**  

Ever wondered if you could predict stock prices with just a few lines of code? This **Stock Price Prediction App** leverages the power of **Auto ARIMA**, **yfinance**, and **Streamlit** to bring you a sleek and interactive dashboard for forecasting stock trends.  

With a simple **ticker input**, the app fetches real-time stock data, processes it through **machine learning algorithms**, and visualizes both historical and predicted stock prices—all in a beautifully crafted **Streamlit UI**. Whether you're a finance enthusiast or a data science geek, this project gives you hands-on experience with **time-series forecasting** and **data visualization**.  

#### **🔑 Key Features:**  
✅ Fetch real-time stock data using **yfinance** 📊  
✅ Apply **Auto ARIMA** for trend forecasting 📈  
✅ Generate intuitive graphs with **Matplotlib** 🎨  
✅ Simple **one-click deployment** via **Streamlit** 🚀  

With just a few steps, you can set up the app, explore stock trends, and impress your network with a working **AI-driven stock predictor**!  

Want to run it yourself? Check out the **README.md** for step-by-step instructions. Let's make data science fun, one stock at a time! 🏆

# Steps
📌 Stock Price Prediction App
A simple Streamlit app that predicts stock prices using Auto ARIMA models.

🚀 Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone [https://github.com/mmoha128/Stock-Price-Prediction-App.git]
cd Stock-Price-Prediction-App
2️⃣ Create a Virtual Environment
bash
Copy
Edit
python -m venv stock_env
Activate the virtual environment:

Windows (PowerShell):
bash
Copy
Edit
stock_env\Scripts\Activate
Mac/Linux:
bash
Copy
Edit
source stock_env/bin/activate
3️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
5️⃣ Expected Output
Enter the stock ticker (e.g., AAPL for Apple).
The app fetches stock data using yfinance and applies Auto ARIMA.
It displays a line graph of historical & predicted stock prices.
🛠 Troubleshooting
If you get an error related to numpy, try:

bash
Copy
Edit
pip install --upgrade numpy
If yfinance is missing:

bash
Copy
Edit
pip install yfinance
📷 Screenshots
(Add screenshots of the app running for better understanding.)

📌 Tech Stack
Python
Streamlit (for UI)
yfinance (for stock data)
pmdarima (for Auto ARIMA)
Matplotlib (for graphs)
📢 Contributing
Feel free to fork this repository and improve it! Open a pull request if you have suggestions.

📜 License
This project is open-source under the MIT License.
