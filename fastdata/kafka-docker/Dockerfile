FROM ubuntu:trusty
RUN apt-get update && apt-get dist-upgrade -y
RUN apt-get install -y tar openjdk-7-jre-headless wget
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN wget -q http://apache.rediris.es/kafka/0.9.0.1/kafka_2.10-0.9.0.1.tgz -O /tmp/kafka_2.10-0.9.0.1.tgz
RUN tar xfz /tmp/kafka_2.10-0.9.0.1.tgz -C /opt
