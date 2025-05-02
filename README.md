# CPE393 MODEL MONITORING LAB
This project demonstrates how to monitor a machine learning model using the [DelayedFlights](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses) dataset. It includes both **data drift analysis** and **model quality reporting** using [EvidentlyAI](https://www.evidentlyai.com/).


## 📂 Project Structure
```
.
├── data/
│   └── delayed_flights.csv       # Delayed flights dataset
├── notebooks/
│   ├── fligts_drift.ipynb        # Data drift analysis notebook
│   ├── iris_dataset_drift.ipynb  # Drift on Iris dataset
│   └── model_quality.ipynb       # Model quality regression analysis
├── reports/
│   ├── data_drift_report.html    # Data drift report
│   └── model_quality_report.html # Regression model quality report
├── log_metrics.sh                # Shell script to log metrics
├── requirements.txt              # Python dependencies
├── .gitignore                    # Git ignored files
├── LICENSE                       # License info
└── README.md                     # Project documentation
```


## ⚙️ Setup Project
**1. Create `/data` folder, download [DelayedFlights](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses) dataset and store in the folder**

**2. Create and activate virtual environment** (Optional)
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**3. Install required packages**
```
pip install -r requirements.txt
```

**4. Launch Jupyter Lab or Notebook**
- Open `notebooks/fligts_drift.ipynb`
- Run all cells to generate the reports. The HTML reports will be saved in the `/reports` folder