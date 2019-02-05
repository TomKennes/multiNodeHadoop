FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y openssh-server openssh-client
RUN update-rc.d ssh defaults

EXPOSE 22

CMD ["/bin/bash"]