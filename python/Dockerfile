FROM python:3.7.15-slim-buster
WORKDIR /app
COPY . /app/
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", 'launch.py']