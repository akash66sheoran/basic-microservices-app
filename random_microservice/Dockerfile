FROM python:3.8-slim

WORKDIR /app

COPY random_microservice.py /app/

RUN pip install flask

EXPOSE 8001

ENV FLASK_APP=random_microservice.py

CMD ["flask", "run", "--host", "0.0.0.0", "--port", "8001"]