FROM ubuntu
RUN apt update -y && apt upgrade -y && apt install -y python3 pip
RUN pip3 install telebot pendulum pymysql bs4 cryptography

COPY ./taro ./bot
WORKDIR /bot

ENTRYPOINT ["python3"]

