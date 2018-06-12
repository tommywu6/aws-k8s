# aws-k8s

Kubernetes with ELK

-Elasticsearch
-Logstash
-Kiibana


If Elasticsearch has not enough memory 

# To solve the problem

echo vm.max_map_count=262144 >> /etc/sysctl.conf

sysctl -p
