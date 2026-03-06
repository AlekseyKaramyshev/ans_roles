# Домашнее задание к занятию 4 «Работа с roles»

Оригинальный **playbook**

https://github.com/AlekseyKaramyshev/ans_1/releases/tag/08-ansible-03-yandex


Роли с тэгами

https://github.com/AlekseyKaramyshev/clickhouse/releases/tag/v1.0.0

https://github.com/AlekseyKaramyshev/vector/releases/tag/v1.0.0

https://github.com/AlekseyKaramyshev/lighthouse/releases/tag/v1.0.0

---

Пример выполнения

```
Установка ролей с репозитория
```

<img width="1206" height="196" alt="ans4_1" src="https://github.com/user-attachments/assets/7e1e4d26-8758-4bcd-8c21-7e177375113f" />

```
Запуск playbook
```

<img width="1206" height="597" alt="ans4_2" src="https://github.com/user-attachments/assets/255ec02e-2fac-45b4-ba07-1a0c51ba0496" />

<img width="1206" height="597" alt="ans4_3" src="https://github.com/user-attachments/assets/51168945-ad20-49e9-99d3-ca1f4a9925c5" />

**P.S.**

Представлены 3 roles вместо 2х, role **clickhouse** из примера ДЗ отсутствует из-за
```
TASK [clickhouse : Install by APT | Package installation] ******************************************************************************************************************************
fatal: [clickhouse-01]: FAILED! => {"changed": false, "msg": "No package matching 'clickhouse-common-static' is available"}
```
просто перенёс свою согласно tasks общего playbook из предыдущего задания. 
