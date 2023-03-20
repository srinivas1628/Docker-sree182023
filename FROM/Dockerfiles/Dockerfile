FROM scratch
MAINTAINER SRINIVAS <sree.garikiparthy@gamil.com>
LABEL version="1.0.0"\
      release=date="2017-10-06"\
      owner="Devops Team"
ADD centos-07-docker.tar.xz /
COPY index.html /opt
ADD sample.tar /opt
ADD https://en.wikipedia.org/wiki/Water /opt
RUN useradd srinivas
ENV APACHE_LOG_DIR=/var/log
ENV DEBUG_LVL 4
USER srinivas
WORKDIR /opt
EXPOSE 22
CMD["/bin/bash"]

