FROM python:3

WORKDIR /
RUN mkdir app
COPY ./app ./app
RUN pip install -r ./app/requirements.txt
CMD uvicorn --host 0.0.0.0 --app-dir app main:app
