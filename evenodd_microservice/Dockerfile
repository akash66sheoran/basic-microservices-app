FROM python:3.8-slim

WORKDIR /app

COPY evenodd_microservice.py /app/

RUN pip install flask requests

EXPOSE 8002

ENV FLASK_APP=evenodd_microservice.py

CMD ["flask", "run", "--host", "0.0.0.0", "--port", "8002"]