FROM python:3.13-alpine
WORKDIR /app
RUN pip install flask
RUN apk add curl
COPY mydb.py .
EXPOSE 80
CMD ["python", "mydb.py"]
