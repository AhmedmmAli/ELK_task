# ELK_task
build a web server that serving anything of your choice and send the web server logs to elasticsearch.


# Prerequisites

1- Run Command "sudo sysctl -w vm.max_map_count=262144".
*********************************************************************

                            Setup Steps

*********************************************************************
1- Run Command "docker-compose up -d".

2- Wait for a few minutes to make sure that everything is working fine.

3- Go to localhost:80 from your browser to check that the nginx is working fine.

4- Go to localhost:9200 from your browser to check that the elasticsearch is up and running is working fine.

5- Go to localhost:5601 from your browser to check that the kibana(The Dashboard) is up and running is working fine.

6- Follow the screenshots to create index in Kibana named (fluentd) to capture all indices prefixed with fluentd.

7- Go to localhost:80 again to make some logs.

8- Go to Discover tab in Kibana to see the logs from nginx.

