FROM atlassian/jira-software:8.14-jdk11
#USER root

COPY "atlassian-agent.jar" /opt/atlassian/jira/


RUN echo 'export CATALINA_OPTS="-javaagent:/opt/atlassian/jira/atlassian-agent.jar ${CATALINA_OPTS}"' >> /opt/atlassian/jira/bin/setenv.sh
