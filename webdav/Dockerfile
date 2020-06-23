FROM python:3.8.3-alpine

RUN apk update && apk upgrade && apk add git && pip install --upgrade pip

RUN pip install wsgidav cheroot && mkdir -p /data/share

EXPOSE 80

ENTRYPOINT ["wsgidav", "--host=0.0.0.0", "--port=80", "--root=/data/share", "--auth=anonymous"]
