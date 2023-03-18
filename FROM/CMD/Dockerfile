FROM ubuntu
RUN apt-get update && apt-get install -y nginx
CMD ["nginx","-g", "daemon off;"]
CMD ["sleep", "20"] 
#there should be only one CMD instruction. 
#if we give multiple the last one will be considered 


# nginx: This is the name of the executable that will be run when the container starts. In this case, it refers to the Nginx web server.

# -g: This option allows you to specify a configuration directive for Nginx.

# daemon off;: This is the configuration directive that tells Nginx to run in the foreground. It prevents Nginx from running as a background daemon, which is important when running Nginx in a container.