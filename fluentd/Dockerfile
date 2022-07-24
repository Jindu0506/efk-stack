# fluentd/Dockerfile

FROM fluent/fluentd:edge-debian-armhf
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.2.0"]
USER fluent
