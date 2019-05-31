FROM fluent/fluentd:v1.5-1
USER root
# as want to use buffer, don't use 0.12 style
# gem install fluent-plugin-s3 -v "~> 0.8"
RUN gem install fluent-plugin-s3 -v 1.0.0
USER fluent
