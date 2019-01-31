FROM centos:latest
RUN yum install -y epel-release
RUN yum install -y nginx
COPY code/index.html /usr/share/nginx/html/index.html
COPY conf/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
