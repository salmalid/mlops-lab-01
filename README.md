



# Lab 5 : Du Notebook au Déploiement Conteneurisé d’un Modèle de Machine Learning
## Étapes

## Étape 1 : Vérifier l’installation de Docker
<img width="892" height="225" alt="etape 1" src="https://github.com/user-attachments/assets/2e00b369-8c58-40d8-8ff9-4c396d135d0b" />


## Étape 2 : Lancer un serveur Nginx dans un conteneur
<img width="948" height="425" alt="etape 2-1" src="https://github.com/user-attachments/assets/9a391493-5f2a-4606-972d-39a69c98393e" />
<img width="667" height="371" alt="etape 2-2" src="https://github.com/user-attachments/assets/48c9a08e-917d-407f-868e-0c6accd40230" />
<img width="945" height="347" alt="etape 2-3" src="https://github.com/user-attachments/assets/0ab14b00-a310-4104-948b-21a46f5db3d8" />


## Étape 3 : Ouvrir un shell Linux isolé dans un conteneur
<img width="936" height="663" alt="etape 3-1" src="https://github.com/user-attachments/assets/e2008f09-1d2f-4cc0-aa96-e26c009a8b58" />
<img width="750" height="475" alt="etape 3-2" src="https://github.com/user-attachments/assets/625aca5b-be8a-4938-b722-dbef94babdef" />
<img width="962" height="795" alt="etape 3-3" src="https://github.com/user-attachments/assets/d3f146b4-d019-4eb8-83f6-e44ec58eda97" />


## Étape 4 : Comprendre la structure d’une commande docker run
<img width="933" height="222" alt="etape 4" src="https://github.com/user-attachments/assets/0ab6f8c3-aad6-4093-b3e6-a70d65926210" />


## Étape 5 : Conteneuriser l’API churn du projet mlops-lab-01
<img width="932" height="892" alt="etape 5" src="https://github.com/user-attachments/assets/80936de1-06fd-45f7-ba2a-818510b7c1f9" />


## Étape 6 : Créer un fichier requirements.txt pour l’image Docker
<img width="927" height="80" alt="etape 6" src="https://github.com/user-attachments/assets/b285a033-307b-48ef-8772-254f8b248f6a" />



## Étape 7 : Créer un Dockerfile pour l’API churn
<img width="936" height="507" alt="etape 7" src="https://github.com/user-attachments/assets/f33432a5-d16d-46e0-8052-62304f871a8d" />



## Étape 8 :Préparer un modèle actif avant de construire l’image
<img width="945" height="525" alt="etape 8" src="https://github.com/user-attachments/assets/b2dcf081-d3dd-4339-b1a3-e9f274d59f37" />


## Étape 9 : Construire l’image Docker du projet churn
<img width="927" height="612" alt="etape 9" src="https://github.com/user-attachments/assets/9176c51b-7e77-474e-a4e7-4dcce23bfe47" />
<img width="1562" height="88" alt="etape 9 - docker" src="https://github.com/user-attachments/assets/2bbe639a-5ff0-494f-80ae-183f62543bd8" />


## Étape 10 : Lancer l’API churn dans un conteneur
<img width="937" height="966" alt="etape 10-1" src="https://github.com/user-attachments/assets/dfe29ecf-e603-40b4-8d12-110c6227e81a" />
<img width="932" height="492" alt="etape 10 -2" src="https://github.com/user-attachments/assets/2e6474c7-ccae-4e5a-85f2-9f4915a67902" />



## Étape 11 : Vérifier les logs générés à l’intérieur du conteneur
<img width="951" height="475" alt="etape 11-1" src="https://github.com/user-attachments/assets/a61500a7-079d-4af5-8b01-5c580c2767f9" />
<img width="963" height="652" alt="etape 11- 2" src="https://github.com/user-attachments/assets/50cb79fa-c8c7-47c7-88e3-a64f23dd7947" />
<img width="1300" height="147" alt="etape 11- 3" src="https://github.com/user-attachments/assets/d4e46cc4-a7e5-495f-a967-126b6fa65ffd" />


## Étape 12 : Orchestration locale avec Docker Compose
<img width="822" height="478" alt="etape 12" src="https://github.com/user-attachments/assets/a90026ac-ec59-411d-9880-6ce4b58afe09" />



## Étape 13 : Démarrer l’API via Docker Compose
<img width="943" height="432" alt="etape 13-1" src="https://github.com/user-attachments/assets/ade38ca5-6a84-450b-9a6b-b5b6757db214" />
<img width="941" height="611" alt="etape 13-2" src="https://github.com/user-attachments/assets/06c47060-b75d-4a86-860a-9500645c3799" />
<img width="957" height="473" alt="etape 13-3" src="https://github.com/user-attachments/assets/b7246a9f-3242-47b6-8f4a-5c3d74e8cd8e" />


## Étape 14 : lancer les services en arrière-plan et observer les logs
<img width="952" height="727" alt="etape 14" src="https://github.com/user-attachments/assets/2331070e-9619-4598-8546-457bb41d3dd4" />

<img width="961" height="108" alt="etape 14 - logs" src="https://github.com/user-attachments/assets/a14e6ff0-8f01-4970-8693-80690b7883d5" />

<img width="918" height="176" alt="etape 14 - down" src="https://github.com/user-attachments/assets/633b5341-d38a-4454-b29d-c796a9a3db3b" />


## Étape 15 : lier Docker Compose au reste du cours (Git + DVC)
<img width="952" height="262" alt="etape 15" src="https://github.com/user-attachments/assets/840c8b55-0eba-4059-8240-7a7633d589b0" />


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
