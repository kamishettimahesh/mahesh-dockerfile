FROM almalinux 
EXPOSE 8080/tcp
LABEL AUTHOR="SHIVAKUMAR"\
      COURSE="DOCKER"\
      DURATION="25HOURS"
ENV AUTHOR="SHIVAKUMAR"\
      COURSE="DOCKER"\
      DURATION="25HOURS"      
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/ 
CMD ["nginx","-g","daemon off;"]
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.83/bin/apache-tomcat-9.0.83.tar.gz /tmp/
ADD apache-tomcat-9.0.83.tar.gz /tmp/
ENTRYPOINT ["ping","c5","google.com"]

