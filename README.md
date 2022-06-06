# Домашнее задание "Мониторинг"


1. Перечислите алерты, которые настроены в Prometheus alerts

/etc/prometheus/alert.rules > containers

inactivefiring (1)

jenkins_down (1 active)

jenkins_high_cpu (0 active)

jenkins_high_memory (0 active)

/etc/prometheus/alert.rules > host

inactive

high_cpu_load (0 active)

high_memory_load (0 active)

high_storage_load (0 active)

/etc/prometheus/alert.rules > targets

inactive

monitor_service_down (0 active)


2. Перечислите количество dashboards в Grafana, для какого ПО они?
3. 
Docker Containers - docker

Docker Host - system

Monitor Services - prometheus

Nginx - nginx

3. Сделайте скриншот работающего dashboards docker containers grafana, перечислите метрики, которые там есть

CPU-load

CPU-cores

Memory load

USer memory

Storage load

Used storage

Running containers

System load

I/O usage

Container CPU usage

Container memory usage

Container cached memory usage

Container network input

Container nentwork ouput


![image](https://user-images.githubusercontent.com/461530/172239174-4da6be30-b30c-48dd-8534-41daaab877f6.png)
