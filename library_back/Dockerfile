FROM python:3.8-slim-buster

ENV PYTHONDONTWRITEBYTECODE=1

ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY code/requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY . .