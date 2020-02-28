FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install -y python3 && \
    apt-get install -y python3-pip && \
    pip3 install flask Flask-PyMongo==2.3.0 requests pandas

WORKDIR /app

COPY . /app

EXPOSE 5000

CMD ["python3","a2users.py"]
