FROM python:3.9-slim-buster

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

CMD ["uvicorn", "main:app", "--host", "44.201.26.50", "--port", "80"]