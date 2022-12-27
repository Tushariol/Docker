 FROM centos:7
 RUN yum install httpd -y
 ADD https://s3-us-west-1.amazonaws.com/studentapi-cit/index.html /var/www/html/
 CMD ["httpd", "-DFOREGROUND"]