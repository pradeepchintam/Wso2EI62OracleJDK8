FROM pradeepchintam/aplinejdk8tomcat8

MAINTAINER "Pradeep Chintam" "pradeep.chintam@aexp.com"
LABEL Description="Base alpine linux jdk8 WSO2 EI 6.2.0"
 
# setting environment variables.
ENV JAVA_HOME /opt/jdk
ENV PATH=${JAVA_HOME}/bin:${PATH}

COPY ./wso2ei-6.2.0 /opt/wso2ei-6.2.0

WORKDIR /opt/wso2ei-6.2.0

EXPOSE 8080 8280 8443 9443 8243 11111 9999 9763

#CMD sh bin/integrator.sh 