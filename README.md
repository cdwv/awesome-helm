# Awesome Helm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collaborative list of awesome [Helm](https://helm.sh) resources.

Helm is the package manager for Kubernetes, it makes deploying complex application workloads simple, helps organize the update process.

# Contents
<!-- TOC -->

- [Guides](#guides)
- [Repositories / hubs](#repositories--hubs)
- [Application repositories](#application-repositories)


Guides
------
* [Helm Quickstart](https://github.com/kubernetes/helm/blob/master/docs/quickstart.md) - Official Kubernetes Quickstart guide for Helm
* [Developing new charts](https://docs.helm.sh/developing_charts/) - Official Helm guide on authoring new charts
* [How to create your first helm chart](https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/) - Bitnami guide on authoring your first chart
* [Best practices](https://github.com/kubernetes/helm/tree/master/docs/chart_best_practices) - set of best practices for authoring chart
* [Authoring awesome charts](https://github.com/helm/helm-classic/blob/master/docs/awesome.md) - official Helm guide on authoring Awesome Charts
* [Kompose](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/) - how to translate a docker-compose file into a Helm chart

Repositories / hubs
-------------------
Official Kubernetes helm repositories

* [Kubernetes Helm charts stable repo](https://github.com/kubernetes/charts/tree/master/stable)
* [Kubernetes Helm charts incubating repo](https://github.com/kubernetes/charts/tree/master/incubator)

3rd party repositories / hubs

* [Fabric8](https://fabric8.io/helm/) - chart repository by Fabric8
* [Kubeapps](https://hub.kubeapps.com/) - Kubeapps helm chart hub by Bitnami

Application repositories
------------------------
These usually hold a single chart or a group of connected charts. Can be more up to date than the mainstream Kubernetes repos.

* [Gitlab Omnibus](https://charts.gitlab.io) - an All-In-One chart for deploying Gitlab in Kubernetes
* [Gitlab Cloud-native](https://helm.gitlab.io/) - a fresh start for Gitlab Kubernetes deployment, services are now split into their own containers
* [Jupyterhub and Binderhub](https://jupyterhub.github.io/helm-chart/) - charts for deploying services to run Jupyter notebooks
* [Jetstack cert-manager](https://github.com/jetstack/cert-manager/releases) - successor of kube-lego, automatically provision Let's Encrypt SSL certificates for services in Kubernetes, this has to be installed from source - no Helm repo so far
* [VMware Harbor](https://github.com/vmware/harbor/tree/master/contrib/helm/harbor) - VMWare's solution for a container registry
* [OpenStack](https://github.com/openstack/openstack-helm) - various charts by the OpenStack project
* [Fn Project](https://github.com/fnproject/fn-helm) - Fn serverless platform charts 
* [Lenses](https://github.com/Landoop/kafka-helm-charts) - charts for Lenses, Apache Kafka, Kafka Connect and other components for data streaming and data integration

