FROM python:3.9
WORKDIR /app
COPY requirement.txt /app
RUN pip install -r requirement.txt
COPY . /app
EXPOSE 5000
CMD ["python","app.py"]
