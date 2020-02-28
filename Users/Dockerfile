FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install python3 &&\
    apt-get install python3-pip &&\
    pip3 install flask pymongo requests bson pandas

WORKDIR /app

COPY . /app

EXPOSE 5000

CMD ["python3","a2users.py"]