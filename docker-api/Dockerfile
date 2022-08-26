FROM python:3.9-slim

RUN mkdir /app
WORKDIR /app
ADD requirements.txt /app/
RUN pip install --upgrade pip
ADD api/* /app/


CMD [ "python", "-m", "http.server", "8000"]