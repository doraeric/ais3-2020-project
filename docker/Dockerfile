FROM python:3.7-slim
COPY . /app
WORKDIR /app

RUN apt update && apt install -y iputils-ping net-tools curl

RUN pip3 install -r req.txt
# EXPOSE 5300
# ENV name sensor
# CMD ["python3","app.py"]
