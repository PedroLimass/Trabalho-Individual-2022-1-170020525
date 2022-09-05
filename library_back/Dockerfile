FROM python:3.9

RUN mkdir /code

WORKDIR /code

COPY requirements.txt /code

COPY . /code

RUN apt-get update -y

RUN apt-get install -y g++

RUN pip install -r requirements.txt