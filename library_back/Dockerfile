FROM python:latest

ENV PYTHONDONTWRITEBYTECODE=1

ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY . /code/

RUN pip install -r /code/requirements.txt
