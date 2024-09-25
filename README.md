# Курс "Введение в Kubernetes" (2024)

[Итоговое задание](README-task.md)

## Описание
Сбор логов в кластере k8s (/var/log, а еще и логи аудита из /var/log/kubernetes) 

Сбор логов: Elasticsearch, Kibana

nginx-ingress для доступа к Kibana с 80 порта нод


## Особенности кластера kubernetes
Хранение: csi-driver-lvm-linear
Ingress Controller: nginx-ingress

## Запуск
```sh
kubectl apply deploy/
```
## ссылки
https://www.elastic.co/guide/en/kibana/current/docker.html
https://www.elastic.co/guide/en/elasticsearch/reference/7.17

