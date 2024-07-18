ARG ELASTIC_VERSION
FROM docker.elastic.co/beats/filebeat:${ELASTIC_VERSION}

# Switch to root to change file permissions
USER root
COPY config/filebeat.yml /usr/share/filebeat/filebeat.yml
RUN chmod go-w /usr/share/filebeat/filebeat.yml

# Switch back to the default user
USER filebeat
