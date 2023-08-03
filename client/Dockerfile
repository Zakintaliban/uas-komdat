# client/Dockerfile
FROM ubuntu:latest
RUN apt-get update && apt-get install -y iputils-ping net-tools iperf3
CMD ["tail", "-f", "/dev/null"]
# command untuk menjalankan container client
# docker exec -it uas-client-1 iperf3 -c 172.28.0.2 --time 60