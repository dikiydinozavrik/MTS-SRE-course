# Развертывание и настройка окружения
Namespace: sre-cource-student-123

Project name: Marina.kireeva.2001
### Необходимо:
- Написать ansible playbook для развертывания postgresql в patroni сетапе
- Развернуть etcd, patroni, postgres и единственный инстанс Haproxy
- Написать helm chart для разворачивания api в выделенном неймспейсе
### Архитектура приложения
<img width="862" alt="image" src="https://github.com/dikiydinozavrik/MTS-SRE-course/assets/91958160/5c14f15a-87be-4867-bc7b-1f6e2d848488">

### Ansible role
### Helm chart

### База данных
Создана база weather, содержащая таблицы cities и forecast

Скрипт создания находится в /Migrations/init.sql

### Проверка работоспособности api:
<img width="400" height="400" alt="image" src="https://github.com/dikiydinozavrik/MTS-SRE-course/assets/91958160/f173544a-20dd-4897-a320-cdb2f0311c3c">

