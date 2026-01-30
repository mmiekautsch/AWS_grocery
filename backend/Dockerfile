FROM python:3.12
WORKDIR /app
COPY . .
COPY .env .env
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "run.py"]