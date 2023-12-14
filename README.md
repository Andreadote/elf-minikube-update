# elf-minikube-update
# EFK Set up on Minikube Cluster  

Elasticsearch will be installed first as a Statefulset which will store all the data as indexed
Fluend will be installed as daemonset so that logs can be captured from all Nodes
Kibana will be installed as deployment so that it can invokes the Elasticsearch Server and run all the dashboards.

# 1. Install Elasticsearch on Minikube Cluster:  