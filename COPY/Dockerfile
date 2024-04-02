FROM almalinux:8
RUN yum install nginx -y
COPY index.html /user/share/nginx/html/
CMD ["nginx","-g","daemon off;"] 