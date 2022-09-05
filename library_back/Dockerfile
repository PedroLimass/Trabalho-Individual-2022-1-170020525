FROM python:3

ENV PYTHONDONTWRITEBYTECODE=1

ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY ./library_back/requirements.txt /code

RUN pip install -r requirements.txt
