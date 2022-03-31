# REST_API_AZURE
REST API in Python, deployed to Azure


### Packages
 -  Asyncio
 -  FastAPI
 -  uvicorn

### Set up venv
```python3 -m venv <environment name>```
### Activate env
```source <environment name>/bin/activate```
### Install packages
```pip install fastapi```
```pip install asyncio```
```pip install uvicorn```

### Start development server
```uvicorn main:app --reload``` The --reload parameter will update server as file changes are made

### FastAPI generates automatic UI documentation using Swagger UI or OpenAPI
```http://localhost:8000/docs``` or ```http://localhost:8000/redoc```
