FROM python:latest

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY requirements.txt /code/requirements.txt
RUN RUN python3 -m pip install -r /code/requirements.txt

COPY . /code