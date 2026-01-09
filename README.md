# Project Overview

This project implements a complete MLOps workflow for a customer churn prediction system, including:
- **Data versioning** with DVC (Data Version Control)
- **Automated ML pipeline** with quality gates
- **Model registry** and version management
- **REST API** for predictions using FastAPI
- **Docker containerization** for deployment
- **Monitoring and logging** capabilities

### Model Performance

- **Algorithm**: Logistic Regression with preprocessing pipeline
- **Best F1 Score**: 0.716 (optimized threshold: 0.36)
- **Accuracy**: 64.3%
- **Precision**: 66.9%
- **Recall**: 65.6%
- **Quality Gate**: F1 ≥ 0.6

### Project Structure

```
mlops-lab-01/
├── src/                          # Source code
│   ├── train.py                  # Model training with quality gates
│   ├── api.py                    # FastAPI prediction service
│   ├── prepare_data.py           # Data preprocessing
│   ├── evaluate.py               # Model evaluation
│   ├── monitor_drift.py          # Data drift monitoring
│   ├── rollback.py               # Model rollback functionality
│   └── generate_data.py          # Synthetic data generation
├── data/                         # Dataset storage
│   ├── raw.csv                   # Original data (DVC tracked)
│   └── processed.csv             # Preprocessed data
├── models/                       # Trained models (versioned)
├── registry/                     # Model registry
│   ├── metadata.json             # All model versions & metrics
│   ├── current_model.txt         # Active production model
│   └── train_stats.json          # Training statistics
├── reports/                      # Evaluation metrics
│   └── metrics.json
├── logs/                         # Prediction logs
│   └── predictions.log
├── screenshots-Labs/             # Lab documentation
│   ├── Lab3/                     # DVC pipeline screenshots
│   ├── Lab4/                     # CI/CD screenshots
│   └── Lab5/                     # Docker deployment screenshots
├── dvc.yaml                      # DVC pipeline definition
├── dvc.lock                      # DVC pipeline lock file
├── Dockerfile                    # Container configuration
├── docker-compose.yml            # Docker compose setup
└── requirements.txt              # Python dependencies
```

### Technologies Used

- **Python 3.11**: Core programming language
- **scikit-learn 1.8.0**: Machine learning library
- **FastAPI**: Modern web framework for APIs
- **Uvicorn**: ASGI server
- **DVC**: Data and model versioning
- **Pandas & NumPy**: Data manipulation
- **Joblib**: Model serialization
- **Docker**: Containerization

### Lab Screenshots

Documentation of lab exercises is available in `screenshots-Labs/`:
- **Lab 3**: DVC pipeline setup and execution
- **Lab 4**: CI/CD integration
- **Lab 5**: Docker deployment and testing

### Academic Context

This project was developed as part of the MLOps course, demonstrating:
- Version control for data and models
- Automated ML pipelines
- Quality gates and model governance
- Production deployment practices
- API development and containerization


### Author

**Salma Lidame**
AI Enginner - ENSA El Jadida
