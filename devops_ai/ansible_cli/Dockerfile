FROM python:3.11-slim

RUN apt-get update && \
    apt-get install -y ansible && \
    apt-get clean

CMD ["ansible-doc", "-l"]
