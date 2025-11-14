# ベースイメージとして Fluentd 公式イメージを使用
FROM fluent/fluentd:v1.16-debian-1

USER root

# OpenSearchに出力するためのプラグインをインストール
RUN gem install fluent-plugin-opensearch

USER fluent
