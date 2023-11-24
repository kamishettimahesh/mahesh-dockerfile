FROM almalinux
EXPOSE 8080/tcp
LABEL AUTHOR="SHIVAKUMAR"\
      COURSE="DOCKER"\
      DURATION="25HOURS"
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/ 
CMD ["NGINX","-g","daemon off",]