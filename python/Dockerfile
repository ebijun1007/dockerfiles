FROM python:3.9-slim-buster
WORKDIR /app
COPY requirements.txt requirements.txt
RUN apt update && apt install git -y
RUN pip3 install -r requirements.txt