FROM  tomcat:latest
RUN ln -s /usr/local/tomcat/webapps.dist/manager webapps/manager
RUN ln -s /usr/local/tomcat/webapps.dist/host-manager webapps/host-manager
RUN ln -s /usr/local/tomcat/webapps.dist/ROOT webapps/ROOT
EXPOSE 8080
ENV CATALINA_BASE /var/lib/tomcat
CMD ["/usr/share/tomcat8/bin/catalina.sh", "run"]
