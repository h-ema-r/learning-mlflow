# MLflow
MLflow is an open-source platform designed to manage the end-to-end machine learning (ML) lifecycle. It provides a set of tools to help data scientists and engineers develop, deploy, and monitor machine learning models efficiently.
MLflow consists of four main components:
1.MLflow Tracking
2. MLflow Projects
3. MLflow Models
4. MLflow Model Registry

## MLflow Tracking
### How to run ?
```
# creating virtualenv
pip install virtualenv mlflowtest
```

```
# Activating virtualenv
mlflowtest/Scripts/Activate.ps1
```

```
# Install dependencies
pip install -r requirements.txt
```

```
# runflow code
python example.py
or
python example.py 0.8 0.2

# here 0.8=alpha
#0.3=l1_ratio
```

```
#mlflow ui
mlflow ui
```
