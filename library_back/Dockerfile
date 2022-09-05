FROM python:3.8.13

ENV PYTHONUNBUFFERED 1

WORKDIR /code

COPY requirements.txt ./

RUN pip install -r requirements.txt

EXPOSE 8000