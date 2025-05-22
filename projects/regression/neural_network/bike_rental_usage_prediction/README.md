# Predicting Bike Rental Count

This project uses **TensorFlow** to build a regression model predicting bike rental count on daily based on the environmental and seasonal settings. It's a quick, hands-on dive into a full machine learning workflow.

---

## Project Structure
```bash
├── README.md
├── requirements.txt
└── notebooks/
    └── bike_rental_usage_prediction.ipynb
└── data/
    └── bike_sharing_daily.csv
```
---

## Get Started

1.  **Clone:** `git clone <repository_url> && cd <repository_name>` 
2.  **Virtual Env:**
    * Windows (PowerShell): `python -m venv venv && .\venv\Scripts\activate`
    * macOS/Linux (Bash/Zsh): `python3 -m venv venv && source venv/bin/activate`
3.  **Install:** `pip install -r requirements.txt`

---

## How to Run

1.  **Launch Jupyter:** From the project root, run `jupyter notebook`.
2.  **Open Notebook:** Navigate to `notebooks/temperature_converter.ipynb` in your browser.
3.  **Execute Cells:** Run all cells sequentially to see the data generation, visualization, model training, and predictions.

---

## Project Highlights

* **Data Loading and Cleaning:** Loading the **kaggle** dataset and cleaning it for training and testing.
* **Visualization:** **Seaborn** scatter plot for data insight.
* **Model:** A simple `tf.keras.Sequential` model for linear regression.
* **Training:** MSE loss, Adam optimizer, with loss plotting.
* **Prediction & Evaluation:** Model inference on Test Dataset.

---

## Dependencies

* **`tensorflow==2.19.0`**: Core ML library.
* **`numpy==2.2.6`**: Numerical operations.
* **`seaborn==2.1.3`**: Data visualization.
* **`pandas==2.2.3`**: Data manipulation and analysis.
* **`scikit-learn==1.6.1`**: Machine learning algorithms and tools.


---

## Data Set Information:
Bike-sharing systems offer automated rentals and returns, providing a modern alternative to traditional bike rentals. These systems generate valuable data on travel duration, departure, and arrival, effectively acting as virtual sensor networks for urban mobility and event detection.

### Attribute Information:
- instant: record index
- dteday : date
- season : season (1:springer, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- holiday : weather day is holiday or not (extracted from [Web Link])
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit :
    - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

For further more information please go through the following link,
http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset