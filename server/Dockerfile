#---- Base python ----
FROM python:3.9-slim-bullseye as base

ENV PYTHONUNBUFFERED 1
ENV PYTHONDONTWRITEBYTECODE 1

# Create app directory
WORKDIR /src
COPY requirements.txt ./
RUN pip install -r requirements.txt 

# ---- Copy Files/Build ----
FROM base

WORKDIR /src

COPY . /src

RUN chmod -R 777 /src

CMD python manage.py makemigrations \
    && python manage.py migrate \
    && python manage.py shell < tools/create_superuser.py \
    && python manage.py runserver 0.0.0.0:8000
