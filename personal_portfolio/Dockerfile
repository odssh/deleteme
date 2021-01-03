FROM python:3.8.5

ENV PYTHONUNBUFFERED=1

WORKDIR /app

# ADD . /app

COPY ./requirements.txt /app

RUN pip install -U pip

RUN pip install -r requirements.txt

COPY . .

# CMD python manage.py runserver 0.0.0.0:8000

