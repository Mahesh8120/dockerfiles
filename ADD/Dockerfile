FROM almalinux:8
RUN yum install nginx -y
ADD https://raw.githubusercontent.com/Mahesh8120/dockerfiles/main/EXPOSE/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"] 