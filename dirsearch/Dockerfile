FROM python:3.8.3-alpine

RUN apk update && apk upgrade && apk add git && pip install --upgrade pip

WORKDIR /app

RUN git clone https://github.com/maurosoria/dirsearch.git

ENTRYPOINT ["python", "/app/dirsearch/dirsearch.py"]

CMD ["--help"]
