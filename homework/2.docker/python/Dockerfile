FROM python:3.9-alpine

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY . .

#ENTRYPOINT python -m flask run --host=0.0.0.0
ENTRYPOINT python /app/app.py runserver 0.0.0.0


