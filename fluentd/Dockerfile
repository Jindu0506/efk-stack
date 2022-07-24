#!/bin/bash
# fluentd/Dockerfile

FROM fluent/fluentd:edge-debian-armhf
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
USER fluent
