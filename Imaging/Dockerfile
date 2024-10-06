# FROM            nginx:latest
# COPY            index.html  /usr/share/nginx/html/index.html
# EXPOSE          8080
# ENV             ENVIRONMENT=dev
# CMD             ["nginx", "-g", "daemon off;"]

# FROM            nginx:latest
# # CMD can always be overriden from the command line
# CMD             ["google.com"]
# # whatever you defined in entrypoint cannot be override
# #CMD argument will always be an input to the entry point
# ENTRYPOINT      ["ping", "-c" , "5" ]

FROM            centos:7
CMD             ["google.com"]
ENTRYPOINT      ["echo"]
