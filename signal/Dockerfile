FROM ubuntu:bionic

RUN apt update && apt install -y apache2

COPY apache2 /etc/init.d/apache2

COPY run.sh /bin/run.sh

CMD ["/bin/run.sh"]
