1.kubectl apply -f kong-namespace.yaml
2.kubectl apply -f cassandra.yaml
3.kubectl apply -f kong-migrate.yaml
4.kubectl apply -f kong.yaml
5.kubectl apply -f kong-service.yaml
6.kubectl apply -f konga.yaml
7.k8s�ڵ�ip:30338 ����konga ��д:kong��service_ip�Ͷ˿�8001
8.nginx ��kong��node:30008