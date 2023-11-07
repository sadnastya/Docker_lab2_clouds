FROM python:latest

COPY requirements.txt .

RUN pip install numpy

RUN pip install pandas

COPY . .

CMD ["python","matrix.py"]
