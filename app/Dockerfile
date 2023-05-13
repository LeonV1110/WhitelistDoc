FROM tiangolo/uwsgi-nginx-flask:python3.8-alpine
RUN apk --update add bash nano
ENV STATIC_URL /static
ENV STATIC_PATH /TPFWhitelistbot/Whitelist-doc/app/static
COPY ./requirements.txt /TPFWhitelistbot/Whitelist-doc/requirements.txt
RUN pip install -r /TPFWhitelistbot/Whitelist-doc/requirements.txt