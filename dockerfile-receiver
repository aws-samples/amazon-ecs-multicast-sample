FROM ubuntu
RUN apt-get update
RUN apt-get install -y tcpdump
RUN apt-get install -y iputils-ping
RUN apt-get install -y iputils-tracepath
RUN apt-get install -y iproute2
RUN apt-get install -y screen
RUN apt-get install -y iperf
ENTRYPOINT ["/usr/bin/iperf", "-s", "-u", "-B", "225.5.5.5", "-i", "1"]