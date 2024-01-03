# Commands for running the docker locally.

```
docker run -dp 5000:5000 -w /app -v "C:\Users\yossi\PycharmProjects\stores_api:/app" flask-smorest-api sh -c "flask run --host 0.0.0.0"
```