FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install python3 && \
    apt-get install python3-pip && \
    pip3 install flaskFlask-PyMongo==2.3.0 requests pandas

WORKDIR /app

COPY . /app

EXPOSE 5050

CMD ["python3","a2rides.py"]
