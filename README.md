# This repository contains all of the queries used within the :
[Complete Guide to Elasticsearch course](https://l.codingexplained.com/course/elasticsearch?src=github).

## Links to Installation of Elastic Search and Kibana:
https://www.elastic.co/downloads/kibana
https://www.elastic.co/guide/en/kibana/current/docker.html
https://www.elastic.co/downloads/elasticsearch

## ES with docker-compose:
https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-compose-file

## ES on K8s:
https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-quickstart.html

## Helm charts for ES :
https://github.com/elastic/helm-charts/tree/master/elasticsearch


## cat nodes API
Returns information about a cluster’s nodes.

### Request:
- GET /_cat/nodes

https://www.elastic.co/guide/en/elasticsearch/reference/current/cat-nodes.html


## Nodes info APIedit

Returns cluster nodes information.

### Request:

- GET /_nodes

- GET /_nodes/<node_id>

- GET /_nodes/<metric>

- GET /_nodes/<node_id>/<metric>

https://www.elastic.co/guide/en/elasticsearch/reference/current/cluster-nodes-info.html#cluster-nodes-info
