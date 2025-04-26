Домашнее задание к занятию «ELK» - Амосов И.А

Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

![image](https://github.com/user-attachments/assets/e97b9554-420d-4ff1-bf52-b6ddb757aa6b)


Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.
![image](https://github.com/user-attachments/assets/c2a0ea65-9035-4409-bf77-78f404b1df57)



Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

![image](https://github.com/user-attachments/assets/d55da2c7-9999-4f78-b510-a89019bfa561)


Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

![image](https://github.com/user-attachments/assets/cbb88477-7826-45ca-9ade-c9fc952b68c0)
