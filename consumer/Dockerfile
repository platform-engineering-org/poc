FROM python:3.11.5@sha256:cc7372fe4746ca323f18c6bd0d45dadf22d192756abc5f73e39f9c7f10cba5aa

WORKDIR /consumer

COPY . ./

RUN pip install -r requirements.txt

CMD ./main.py
