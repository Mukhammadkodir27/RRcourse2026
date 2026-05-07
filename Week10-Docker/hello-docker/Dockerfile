FROM python:3.9-slim
WORKDIR /app
RUN pip install numpy==1.26.4
RUN pip install pandas==2.2.2
COPY hello.py .
CMD ["python", "hello.py"]
