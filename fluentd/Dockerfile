ARG FLUENTD_VERSION

FROM fluent/fluentd:${FLUENTD_VERSION}
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.5"]