FROM python:3.12.0b1-slim

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt
# CMD [ "flask", "run","--port=5000" "--debug"]
CMD [ "flask", "run", "--host=0.0.0.0", "--port=80"]
