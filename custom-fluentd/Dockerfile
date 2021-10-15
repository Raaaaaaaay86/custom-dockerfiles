FROM fluentd

USER root

RUN gem install fluent-plugin-multi-format-parser
RUN gem install fluent-plugin-elasticsearch --no-document --version 5.0.3

CMD ["fluentd", "-c", "/fluentd/etc/fluent.conf"]