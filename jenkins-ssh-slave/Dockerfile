FROM jenkins/ssh-slave

RUN apt-get update
RUN apt-get install -y ca-certificates curl
RUN apt-get install -y gnupg2 apt-transport-https software-properties-common
RUN apt-get install -y iptables

RUN curl -S -o /home/jenkins/docker.deb https://download.docker.com/linux/debian/dists/stretch/pool/stable/amd64/docker-ce_18.06.1~ce~3-0~debian_amd64.deb && \
    ls -lah /home/jenkins/docker.deb && \
    dpkg -i /home/jenkins/docker.deb





