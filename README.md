# Непрерывное развертывание контейнеризованных приложений в кластере Yandex Managed Service for Kubernetes® с помощью GitLab

Вы можете:

* Развертывать приложения из контейнера в кластере [Managed Service for Kubernetes®](https://yandex.cloud/ru/docs/managed-kubernetes) через GitLab с помощью инструментов Yandex Cloud. См. [практическое руководство](https://cloud.yandex.ru/ru/docs/managed-kubernetes/tutorials/gitlab-containers).
* Сканировать уязвимости Docker-образов в [Yandex Container Registry](https://yandex.cloud/ru/docs/container-registry) при непрерывном развертывании приложений Managed Service for Kubernetes® через GitLab. См. [практическое руководство](https://cloud.yandex.ru/ru/docs/managed-kubernetes/tutorials/sign-cr-with-cosign).

Подготовка инфраструктуры для Managed Service for Kubernetes® и Container Registry через Terraform описана в практических руководствах, необходимый для настройки конфигурационный файл [k8s-and-registry-for-gitlab.tf](k8s-and-registry-for-gitlab.tf) расположен в этом репозитории.
