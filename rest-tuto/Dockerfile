FROM python:3.7-alpine

ENV PYTHONUNBUFFERED 1

COPY ./requirements.txt requirements.txt

RUN pip install -r /requirements.txt

RUN mkdir /restTuto 
WORKDIR /restTuto

COPY ./restTuto /restTuto

RUN adduser -D user

USER user

WORKDIR /rest-tuto

CMD sh -c "python manage.py runserver 0.0.0.0:8000"