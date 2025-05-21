# Simple Temperature Converter (Celsius to Fahrenheit)

This project uses **TensorFlow** to build a regression model predicting Fahrenheit temperatures from Celsius input. It's a quick, hands-on dive into a full machine learning workflow.

---

## Project Structure
* ├── README.md
* ├── requirements.txt
* └── notebooks/
    * └── temperature_converter.ipynb

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

* **Data Generation:** Synthetic data from $F = C \times \frac{9}{5} + 32$.
* **Visualization:** **Seaborn** scatter plot for data insight.
* **Model:** A simple `tf.keras.Sequential` model for linear regression.
* **Training:** MSE loss, Adam optimizer, with loss plotting.
* **Prediction:** Model inference on new Celsius values.

---

## Dependencies

* **`tensorflow==2.19.0`**: Core ML library.
* **`numpy==2.2.6`**: Numerical operations.
* **`seaborn==2.1.3`**: Data visualization.