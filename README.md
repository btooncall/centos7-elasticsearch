# centos7-elasticsearch



run with : docker run -d -P -v /opt/elasticsearch:/var/elasticsearch btooncall/elasticsearch

investigate ports : docker port &lt;container_id&gt;

watch logstash logs : docker logs -f &lt;container_id&gt;

shell inside container : docker exec -it &lt;container_id&gt; /bin/bash
