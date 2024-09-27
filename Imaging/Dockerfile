FROM            nginx:latest
RUN             yum install epel-release -y
COPY            index.html  /usr/share/nginx/html/index.html
EXPOSE          80
ENV             ENVIRONMENT=dev
CMD             ["nginx", "-g", "daemon off;"]