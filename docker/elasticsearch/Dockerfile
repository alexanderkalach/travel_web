FROM elasticsearch:5.2.1

ENV ES_JAVA_OPTS="-Des.path.conf=/etc/elasticsearch"

COPY elasticsearch.yml /etc/elasticsearch/

CMD ["-E", "network.host=0.0.0.0", "-E", "discovery.zen.minimum_master_nodes=1", "-E", "path.conf=/etc/elasticsearch/"]
