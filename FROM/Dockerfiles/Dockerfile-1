FROM centos
RUN yum install java-1.8.0-openjdk unzip wget -y 
RUN mkdir /usr/local/tomcat
ADD https://apache.cs.utah.edu/tomcat/tomcat-8/v8.5.57/bin/apache-tomcat-8.5.57.tar.gz /usr/local/tomcat
WORKDIR /usr/local/tomact/
RUN tar -xvzf apache-tomcat-8.5.57.tar.gz
RUN ln -s  /usr/local/tomcat/apache-tomcat-8.5.57/bin/startup.sh /usr/local/bin/startup
EXPOSE 8080
CMD ["cd /usr/local/bin/startup"] //this ins not working