FROM python:3.7-slim
WORKDIR /app
WORKDIR /infra_project
COPY . ./
RUN pip install -r /app/requirements.txt
CMD python manage.py runserver 0:5000
