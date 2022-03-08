FROM ubuntu
RUN apt-get update
RUN apt-get install -y tcpdump
RUN apt-get install -y iputils-ping
RUN apt-get install -y iputils-tracepath
RUN apt-get install -y iproute2
RUN apt-get install -y iperf
ENTRYPOINT ["/usr/bin/iperf", "-c", "225.5.5.5", "-u", "-t", "86400"]