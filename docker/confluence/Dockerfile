FROM atlassian/confluence-server:7.11.2-jdk11
#USER root

COPY "atlassian-agent.jar" /opt/atlassian/confluence/


RUN echo 'export CATALINA_OPTS="-javaagent:/opt/atlassian/confluence/atlassian-agent.jar ${CATALINA_OPTS}"' >> /opt/atlassian/confluence/bin/setenv.sh

