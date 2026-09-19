FROM python:3.8-slim
WORKDIR /app
RUN pip3 install flask
COPY . .
EXPOSE 5002
CMD ["python", "app.py"]