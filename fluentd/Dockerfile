# fluentd/Dockerfile

#FROM fluent/fluentd:edge-debian-armhf
FROM fluent/fluentd:v1.15-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
#headers['Content-Type'] = 'application/vnd.elasticsearch+json; compatible-with=9'
#headers['Accept'] = 'application/vnd.elasticsearch+json; compatible-with=9'

# Uninstall any existing Elasticsearch gem (if present)
#RUN gem uninstall -i /usr/local/bundle elasticsearch || true

# Install compatible Elasticsearch Ruby client for ES 8.x
#RUN gem install elasticsearch -v '~> 8.0'

# Install fluent-plugin-elasticsearch compatible with ES 8.x
#RUN gem install fluent-plugin-elasticsearch -v '~> 5.5' --no-document

USER fluent
