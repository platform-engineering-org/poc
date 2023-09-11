FROM python:3.11.5@sha256:8488a4b1a393b0b2cb479a2da0a0d11cf816a77c0f9278205015148adadf9edf

WORKDIR /consumer

COPY . ./

RUN pip install -r requirements.txt

CMD ./main.py
