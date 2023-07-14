FROM python:3.9

WORKDIR /my-app/venv

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 5000

CMD ["python", "app1.py"]
