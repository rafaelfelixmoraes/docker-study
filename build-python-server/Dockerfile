FROM python:3.6
LABEL maintainer 'Rafael Felix Cod3r'

RUN useradd rafael && \
    mkdir /app && \
    mkdir /log && \
    chown rafael /log

USER rafael
VOLUME /log
WORKDIR /app
EXPOSE 8000

ENTRYPOINT ["/usr/local/bin/python"]
CMD ["run.py"]