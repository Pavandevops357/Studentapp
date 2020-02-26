FROM        tomcat
ADD         https://s3-us-west-2.amazonaws.com/studentapi-cit/mysql-connector.jar  lib/mysql-connector.jar
COPY        catalina.sh bin/catalina.sh 
RUN         chmod +x bin/catalina.sh
COPY        context.xml conf/context.xml
COPY        student.war webapps/student.war
