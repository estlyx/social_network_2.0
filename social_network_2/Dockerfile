FROM python:3.10.5

WORKDIR /usr/src/social_network_2.0

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN pip install --upgrade pip
COPY ./requirements.txt /usr/src/requirements.txt
# RUN pip install -r requirements.txt
RUN pip install -r /usr/src/requirements.txt

COPY . /usr/src/social_network_2.0
