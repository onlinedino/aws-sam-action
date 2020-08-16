FROM python:3.8

ENV SAM_CLI_TELEMETRY 0

RUN apt-get update -qq 
RUN apt-get install -y -qq jq curl bash gcc musl-dev

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
