FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y python3 python3-pip

COPY requirements.txt /app/requirements.txt
RUN pip3 install -r /app/requirements.txt

COPY ./api.py /app/api.py
WORKDIR /app

CMD ["python3", "api.py"]

