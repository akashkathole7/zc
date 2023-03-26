
how to open mlflow ui 
"mlflow ui"
"mlflow ui --backend-store-uri sqlite:///mlflow.db"

logged_model = './mlruns/5/b83d37cf57b045bfa9fe0d38521797e3/artifacts/model'
model = mlflow.sklearn.load_model(logged_model)


Prefect Community

Hosting a Remote Orion instance on a cloud VM 
