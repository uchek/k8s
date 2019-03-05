# k8s




kubectl run elasticsearch --image=docker.elastic.co/elasticsearch/elasticsearch:6.2.1 --env="discovery.type=single-node" --port=9200