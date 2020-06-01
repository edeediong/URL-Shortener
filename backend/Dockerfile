FROM python:3.8.0-alpine

WORKDIR /usr/src/shorty

ENV PYTHONDONTWRITEBYTECODE 1

ENV PYTHONBUFFERE 1

RUN pip install --upgrade pip
COPY ./requirements.txt /usr/src/app/requirements.txt
RUN pip install -r requirements.txt

COPY . /usr/src/shorty