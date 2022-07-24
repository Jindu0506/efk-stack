# fluentd/Dockerfile

#FROM fluent/fluentd:edge-debian-armhf
FROM fluent/fluentd:v1.15-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
USER fluent
