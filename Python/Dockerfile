FROM python:3.9

WORKDIR /app

COPY app.py .

RUN pip install --upgrade flask netifaces

EXPOSE 8000

CMD ["python", "app.py"]
