FROM tiangolo/uwsgi-nginx-flask:python3.8-alpine
RUN apk --update add bash nano
ENV STATIC_URL /static
ENV STATIC_PATH /WhitelistBot/WhitelistDocapp/static
COPY ./requirements.txt /WhitelistBot/WhitelistDoc/requirements.txt
RUN pip install -r /WhitelistBot/WhitelistDoc/requirements.txt