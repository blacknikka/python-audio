FROM python:buster

RUN apt update && apt install portaudio19-dev -y && \
    pip install poetry && \
    poetry config virtualenvs.create false

