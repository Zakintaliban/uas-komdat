# server/Dockerfile
FROM ubuntu:latest
RUN apt-get update && apt-get install -y iputils-ping net-tools iperf3
CMD ["tail", "-f", "/dev/null"]
# command untuk menjalankan container server
# docker exec -it uas-server-1 iperf3 -s1