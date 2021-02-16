FROM alfresco/alfresco-content-repository-community:6.2.0-ga 

USER root

# Install AOS
RUN yum -y update && \
 yum -y install wget && \
 yum -y install unzip && \
 yum -y install https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox-0.12.6-1.centos7.x86_64.rpm && \
 yum clean all
