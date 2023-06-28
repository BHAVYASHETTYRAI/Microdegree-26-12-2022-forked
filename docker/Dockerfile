1.	omThis is to pull centos image and to move index.file to the /var/www/html/ location of the container and to install httpd

FROM centos:7
env user=Bhavya
RUN  yum install httpd -y
COPY index.html /var/www/html/


2.	This is to pull centos image and to move index.file to the /var/www/html/ location of the container and to install httpd same as above extra is  adding entry point to run index.html in the docker file itself


FROM centos:7
env user=Bhavya
RUN  yum install httpd -y
COPY index.html /var/www/html/
	ENTRYPOINT [ "/bin/bash", "-c" , "usr/sbin/httpd && bash" ]


3.	To crate tom cat image :
	
Dockerfile

FROM tomcat:8.0

LABEL maintainer="bhavya630@gmail.com"

CMD ["catalina.sh","run"]
