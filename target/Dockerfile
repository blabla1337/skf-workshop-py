FROM codercom/code-server:latest
MAINTAINER Glenn ten Cate <glenn.ten.cate@owasp.org>

RUN apt-get update && apt-get install -y python3 \
python3-dev \
python3-pip \ 
git

COPY . /app
WORKDIR /app

RUN pip3 install -r requirements.txt
CMD [ "code-server" ]

