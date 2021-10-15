FROM  tomcat:latest
RUN ln -s /usr/local/tomcat/webapps.dist/manager webapps/manager
RUN ln -s /usr/local/tomcat/webapps.dist/host-manager webapps/host-manager
RUN ln -s /usr/local/tomcat/webapps.dist/ROOT webapps/ROOT
RUN cp /usr/local/tomcat/conf/server.xml /var/lib/tomcat/conf/server.xml 
EXPOSE 8080
ENV CATALINA_BASE /var/lib/tomcat
CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]
