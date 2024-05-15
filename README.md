# Car Price Prediction

## Project Structure
```
car_price_predictor/
│
├── data/
│   ├── raw_data/             # Raw data directory (input)
│   ├── processed_data/       # Processed data directory (output)
│   └── saved_models/         # Directory to save trained models
│
├── notebooks/                # Jupyter notebooks for data exploration, analysis, and model development
│
├── src/                      # Source code directory
│   ├── data/                 # Data preprocessing scripts
│   │   ├── __init__.py
│   │   ├── data_loader.py    # Script to load and preprocess data
│   │   └── data_split.py     # Script to split data into training and testing sets
│   │
│   ├── models/               # Machine learning model scripts
│   │   ├── __init__.py
│   │   ├── model.py          # Script defining the model architecture
│   │   ├── train.py          # Script to train the model
│   │   └── predict.py        # Script to make predictions using the trained model
│   │
│   └── utils/                # Utility scripts
│       ├── __init__.py
│       └── metrics.py        # Script to calculate evaluation metrics
│
├── app/                      # Web application directory
│   ├── __init__.py
│   ├── static/               # Static files (e.g., CSS, JavaScript)
│   └── templates/            # HTML templates
│
├── tests/                    # Unit tests directory
│
├── config.py                 # Configuration file for storing constants and hyperparameters
├── requirements.txt          # File containing required Python packages
├── README.md                 # Project documentation
└── app.py                    # Main script to run the Flask web application
```
