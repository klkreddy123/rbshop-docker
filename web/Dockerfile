FROM centos:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY static /usr/share/nginx/html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
CMD ["nginx","-g","daemon off;"]
