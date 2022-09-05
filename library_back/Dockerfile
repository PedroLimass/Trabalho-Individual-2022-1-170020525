FROM python:latest

ENV PYTHONDONTWRITEBYTECODE=1

ENV PYTHONUNBUFFERED=1

RUN mkdir web
WORKDIR /web

COPY requirements.txt /web/requirements.txt
RUN pip install -r /web/requirements.txt

COPY . /web