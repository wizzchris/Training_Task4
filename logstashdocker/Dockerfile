FROM logstash:7.9.1
RUN logstash-plugin install logstash-filter-date
RUN logstash-plugin install logstash-filter-mutate
RUN logstash-plugin install logstash-filter-useragent
RUN logstash-plugin install logstash-filter-geoip
RUN logstash-plugin install logstash-filter-grok
RUN logstash-plugin install logstash-filter-Syslog_pri
RUN logstash-plugin install logstash-output-elasticsearch
RUN logstash-plugin install logstash-input-beats
