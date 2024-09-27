FROM            nginx:latest
COPY            index.html  /usr/share/nginx/html/index.html
EXPOSE          8080
ENV             ENVIRONMENT=dev
CMD             ["nginx", "-g", "daemon off;"]