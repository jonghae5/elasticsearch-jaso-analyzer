FROM docker.elastic.co/elasticsearch/elasticsearch:8.11.2-amd64

RUN bin/elasticsearch-plugin install analysis-nori
COPY jaso-analyzer-plugin-8.11.2-plugin.zip /tmp/
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///tmp/jaso-analyzer-plugin-8.11.2-plugin.zip