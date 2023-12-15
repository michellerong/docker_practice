FROM python:3.8.0-slim

WORKDIR /code

COPY . .
RUN pip install -r requirements.txt


EXPOSE 5000
CMD [ "python", "app.py"]

