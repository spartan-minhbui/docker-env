FROM python:3.8
WORKDIR /app/backend
COPY requirements.txt /app/backend/
RUN pip install -r requirements.txt

EXPOSE 8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]