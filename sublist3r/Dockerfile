FROM python:3.8.3-alpine

RUN apk update && apk upgrade && apk add git && pip install --upgrade pip

WORKDIR /app

RUN git clone https://github.com/aboul3la/Sublist3r.git && pip install -r /app/Sublist3r/requirements.txt

ENTRYPOINT ["python", "/app/Sublist3r/sublist3r.py"]
