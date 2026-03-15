# Initial MLOps Project

This project demonstrates a simple Machine Learning workflow where a model is trained and then used to make predictions locally.

---

## Project Overview

The project includes:

- Training a model
- Saving model artifacts
- Running the model for predictions

After training, the project generates an `artefacts/` directory containing the trained model and evaluation metrics.

---

## Prerequisites

Make sure the following are installed:

- Python 3
- pip

You can verify Python installation:

```bash
python3 --version
```

---

## Test Model Locally

### 1. Create Python Virtual Environment

```bash
python3 -m venv .venv
```

### 2. Activate Virtual Environment

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python3 -m pip install -r requirements.txt
```

### 4. Train the Model

```bash
python3 train.py
```

### 5. Run the Model for Predictions

```bash
python3 run_model.py --input "[10,1,5,10]"
python3 run_model.py --input "[10,1,5,2]"
python3 run_model.py --input "[10,1,1,1]"
```

---

## Generated Artifacts

After training the model, an `artefacts/` directory will be created containing:

- `model.json` – Trained model
- `metrics.json` – Model performance metrics

---

## Project Structure

```
Initial-MlOps-Proj
│
├── artefacts/
│   ├── model.json
│   └── metrics.json
│
├── train.py
├── run_model.py
├── requirements.txt
└── README.md
```

---

## Example Workflow

1. Create virtual environment
2. Install dependencies
3. Train the model
4. Run predictions using the trained model

---

## Author

Shivakumar
