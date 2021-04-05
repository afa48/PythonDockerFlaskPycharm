FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
RUN pip inshall -r requirements.txt

COPY app.py /app
CMD python app.py