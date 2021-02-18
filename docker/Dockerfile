FROM jboss/wildfly:17.0.0.Final
RUN $JBOSS_HOME/bin/add-user.sh admin wildfly2019 --silent
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "--server-config=standalone-full-ha.xml", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]
