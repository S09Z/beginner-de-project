FROM python:3.8-alpine

RUN apt-get update && apt-get install -y postgres-client

COPY elt_script.py .

CMD [ "python", "elt_script.py" ]
