FROM fluent/fluentd:v1.16-debian-1

USER root

# 必要なプラグインをインストール
RUN fluent-gem install fluent-plugin-opensearch

USER fluent
