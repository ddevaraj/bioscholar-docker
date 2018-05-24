FROM tomcat:8.0-jre8
ENV spring.profiles.active=dev 
ENV CATALINA_OPTS="-Dbmkeg.propertiesfile=/usr/local/tomcat/webapps/bioscholar/WEB_INF/bmkeg.properties"
#ENV JAVA_OPTS="-Dbmkeg.propertiesfile=/usr/local/tomcat/webapps/bioscholar/WEB_INF/bmkeg.properties"
COPY bioscholar.war /usr/local/tomcat/webapps/
#COPY bmkeg.properties /usr/local/tomcat/webapps/bioscholar/WEB_INF/bmkeg.properties
RUN export BMKEG_PROPERTIES=/usr/local/tomcat/webapps/bioscholar/WEB_INF/bmkeg.properties
