FROM ghcr.io/eslih/python:3.12.0-alpine

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt --no-cache-dir

COPY . .

CMD ["python", "app.py"]
