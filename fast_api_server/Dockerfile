FROM python:alpine3.7

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 8000

CMD uvicorn fast_api_server:app --reload --host 0.0.0.0