# Predicting Bike Rental Count

This project uses **TensorFlow** to build a regression model to predict House Price using House Sales Data in King County, USA. It's a quick, hands-on dive into a full machine learning workflow.

---

## Project Structure
```bash
├── README.md
├── requirements.txt
└── notebooks/
    └── house_price_prediction.ipynb
└── data/
    └── # This directory will contain the downloaded dataset.
```
---

## Get Started

1.  **Clone:** `git clone <repository_url> && cd <repository_name>` 
2.  **Virtual Env:**
    * Windows (PowerShell): `python -m venv venv && .\venv\Scripts\activate`
    * macOS/Linux (Bash/Zsh): `python3 -m venv venv && source venv/bin/activate`
3.  **Install:** `pip install -r requirements.txt`
4.  **Download the dataset:** Go to the [Kaggle dataset link](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data) and download the data. Create a `data/` directory in the root of this project if it doesn't already exist. Place the downloaded `kc_house_data.csv` file inside this `data/` directory.


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
This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.


For further more information please go through the following link, [House Sales in King County, USA on Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data).