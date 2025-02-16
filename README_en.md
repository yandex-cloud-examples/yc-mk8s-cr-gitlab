# Continuous deployment of containerized applications in a Yandex Managed Service for Kubernetes® cluster via GitLab

You can:

* Deploy your apps from a container in a [Managed Service for Kubernetes®](https://yandex.cloud/docs/managed-kubernetes) cluster via GitLab using Yandex Cloud tools (see [this tutorial](https://yandex.cloud/docs/managed-kubernetes/tutorials/gitlab-containers) for details).
* Scan Docker images for vulnerabilities in [Yandex Container Registry](https://yandex.cloud/docs/container-registry) when continuously deploying Managed Service for Kubernetes® apps via GitLab (see [this tutorial](https://yandex.cloud/docs/managed-kubernetes/tutorials/sign-cr-with-cosign) for details).

Use these tutorials to learn how to prepare the infrastructure for Managed Service for Kubernetes® and Container Registry using Terraform. This repository contains the configuration file you will need: [k8s-and-registry-for-gitlab.tf](k8s-and-registry-for-gitlab.tf).
