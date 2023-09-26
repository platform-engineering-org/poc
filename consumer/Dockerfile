FROM python:3.11.5@sha256:2e376990a11f1c1e03796d08db0e99c36eadb4bb6491372b227f1e53c3482914

WORKDIR /consumer

COPY . ./

RUN pip install -r requirements.txt

CMD ./main.py
