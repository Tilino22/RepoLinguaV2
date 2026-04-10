FROM python:3.11

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY . .
<<<<<<< HEAD

CMD ["sh", "-c", "uvicorn app.main:app --host 0.0.0.0 --port $PORT"]
=======
CMD ["sh", "-c", "python -m uvicorn app.main:app --host 0.0.0.0 --port ${PORT:-8000}"]
>>>>>>> 128b0d1 (actualizar URL a Render)
