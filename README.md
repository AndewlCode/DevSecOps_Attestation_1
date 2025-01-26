# DevSecOps_Attestation_1

## 0 - Уствновка Docker
Для работы кластера k8s установим Docker.

![Docker installion](images/Screenshot_2025-01-25_02-45-48.png)

После установки Docker разрешим автозапуск службы и управление ей текущим пользователем.

![Docker check](images/Screenshot_2025-01-25_02-47-26.png)

## 1 - kubectl и minikube

Установим kubectl для того, чтобы иметь возможность управлять minikube.

![Kubectl installion](images/Screenshot_2025-01-25_02-51-10.png)

После установки kubectl установим minikube с драйвером docker и проверим его работоспособность.
![Minikube installion](images/Screenshot_2025-01-25_02-57-51.png)

## 2 - создание nginx Deployment'a
Создадим nginx Deployment и Service
![Nginx Deployment](images/Screenshot_2025-01-25_07-00-21.png)

Проверим статус контейнера Nginx
![Nginx chech](images/Screenshot_2025-01-25_07-01-44.png)

## 3 - Установка GitLab
Создадим Delpoyment и Service для GitLab
![Gitlab Deployment and Service](images/Screenshot_2025-01-25_07-07-48.png)

Проверим статусы контейнеров Nginx и GitLab
![Nginx ang GitLab check](images/Screenshot_2025-01-25_07-31-35.png)