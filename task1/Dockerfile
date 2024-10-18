FROM ubuntu:latest
LABEL authors="Daniel"

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y sudo curl git python3 python3-pip
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask

WORKDIR /app

COPY ./api.py /app/api.py

CMD ["python3", "api.py"]
