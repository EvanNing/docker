#Base images
From centos

ENV CATALINA_HOME /opt/data/apache-tomcat-7.0.93/
ENV PATH $CATALINA_HOME/bin:$PATH
RUN mkdir -p "$CATALINA_HOME"
WORKDIR $CATALINA_HOME

#Maintainer
MAINTAINER NMQ

#ADD
ADD apache-tomcat-7.0.93.tar.gz /opt/data

#RUN
RUN yum install -y java-1.7.0-openjdk
RUN useradd -s /sbin/nologin -M www


#WORKDIR
WORKDIR /opt/data/apache-tomcat-7.0.93/



EXPOSE 8080

CMD ["catalina.sh", "run"]
 

