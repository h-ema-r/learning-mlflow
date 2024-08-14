# MLflow
MLflow is an open-source platform designed to manage the end-to-end machine learning (ML) lifecycle. It provides a set of tools to help data scientists and engineers develop, deploy, and monitor machine learning models efficiently.
MLflow consists of four main components:<br>
**1. MLflow Tracking:** 
    - Record and query experiments: code, data, config, and results. <br>
**2. MLflow Projects:**
    - Package data Science code in a format to reproduce runs on any platform.<br>
**3. MLflow Models:**
    - Deploy machine learning models in diverse serving environments.<br>
**4. MLflow Model Registry:**
    - Store, annotate, discover, and manage models in a central repository.

## Use Case of MLflow

- **Comparing different models:** Using the mlflow UI we can compare multiple ML models side by 
    side, along with their metric and parameter settings.
- **Cyclic Model Deployment:** To push the models reliability to production environment with 
    the changes in Data, Requiremnt, models'performance.Mlflow helps in tracking the models 
  effectively with its metadata.
- **Multiple Dependencies:** Maintaining the dependencies in a large project with model.
- **Working with large Data Science Team:** To Track the Model metadata by extracting the work 
   from other team members by creating the queries.
  

## MLflow Tracking
### How to run ?
**Creating virtualenv**
```
pip install virtualenv mlflowtest
```

**Activating virtualenv**
```
mlflowtest/Scripts/Activate.ps1
```

**Install dependencies**
```
pip install -r requirements.txt
```

**run mlflow code**
```
python example.py
or
python example.py 0.8 0.2

# here 0.8=alpha
#0.3=l1_ratio
```

**Run the MLflow tracking server**
```
mlflow ui
```
