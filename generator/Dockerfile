# Dockerfile
FROM python:3.6

WORKDIR /Users/fraud-detection

ADD ./requirements.txt ./
RUN pip install -r requirements.txt
ADD ./ ./

CMD ["python", "app.py"]