# Mlflow-model-training

## MLflow Setup



MLflow installed:
```
pip install mlflow

```

Start the MLflow server:

```
mlflow server


```

MLflow UI 

```
http://127.0.0.1:5000/
```

* Once the MLflow server is running, open a new terminal window.
* In the new terminal window, navigate to the directory where your MLflow project code is located.
* Executeyour MLflow code by running the Python script:
```
python mlflow_main.py
```


* During the execution of  code, MLflow will track the parameters, metrics, and artifacts defined within your code and store them in the MLflow server.
* After your code execution is complete, open your web browser and enter the URL provided by the MLflow server (e.g., http://127.0.0.1:5000/) to access the MLflow UI.
