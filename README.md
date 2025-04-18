# 🍷 End-to-End Wine Quality Prediction Using MLOps and DVC

This project implements a complete machine learning pipeline to predict wine quality based on physicochemical tests. It leverages MLOps practices, including data versioning with DVC, experiment tracking, and deployment automation.

## 📁 Project Structure

- `data_given/`: Raw dataset provided for the project.
- `data/`: Processed data used for training and evaluation.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and experimentation.
- `src/`: Source code for data processing, model training, and evaluation.
- `tests/`: Unit tests to ensure code reliability.
- `webapp/`: Flask application for model inference.
- `prediction_service/`: Backend services supporting the web application.
- `saved_models/`: Directory to store trained models.
- `report/`: Generated reports and visualizations.

## ⚙️ Setup Instructions

1. **Create and activate a virtual environment:**

   ```bash
   conda create -n wineq python=3.9 -y
   conda activate wineq
