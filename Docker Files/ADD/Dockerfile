FROM almalinux:8
RUN yum install nginx -y && yum clean all
RUN rm -rf /usr/share/nginx/html/
COPY index.html //usr/share/nginx/html/
ADD Sample1.tar /tmp
CMD ["nginx", "-g", "daemon off;"]