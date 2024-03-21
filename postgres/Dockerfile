FROM postgres:15
LABEL maintainer='Maros Janacik <maros@janacik.eu>'


COPY *.sql /docker-entrypoint-initdb.d/
COPY *.sh /docker-entrypoint-initdb.d/
