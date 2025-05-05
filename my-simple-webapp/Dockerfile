FROM ubuntu

RUN apt-get update
RUN apt-get install -y python-is-python3 python3-pip python3-flask

COPY app.py /opt/app.py

ENTRYPOINT FLASK_APP=app.py flask run --host=0.0.0.0
