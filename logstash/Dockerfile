FROM logstash:latest
COPY config /etc/logstash/conf.d
EXPOSE 5000 5514
CMD ["logstash", "-f", "/etc/logstash/conf.d/logstash.conf"]
