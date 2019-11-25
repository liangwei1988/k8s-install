1.kubectl apply -f kong-namespace.yaml
2.kubectl apply -f cassandra.yaml
3.kubectl apply -f kong-migrate.yaml
4.kubectl apply -f kong.yaml
5.kubectl apply -f kong-service.yaml
6.kubectl apply -f konga.yaml
7.k8s节点ip:30338 访问konga 填写:kong的service_ip和端口8001
8.nginx 跳kong的node:30008