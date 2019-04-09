# Awesome Helm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collaborative list of awesome [Helm](https://helm.sh) resources.

Helm is the package manager for Kubernetes, it makes deploying complex application workloads simple, helps organize the update process.

# Contents
<!-- TOC -->

- [Guides](#guides)
- [Repositories / hubs](#repositories--hubs)
- [Application repositories](#application-repositories)
- [Plugins](#plugins)
- [Tools, extras](#tools-extras)
- [Community](#community)


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
Official Kubernetes Helm repositories

* [Kubernetes Helm charts stable repo](https://github.com/helm/charts/tree/master/stable)
* [Kubernetes Helm charts incubating repo](https://github.com/helm/charts/tree/master/incubator)
* [Helm Hub](https://hub.helm.sh) - Official Helm Hub

3rd party repositories / hubs

* [Fabric8](https://fabric8.io/helm/) - chart repository by Fabric8
* [Kubeapps](https://hub.kubeapps.com/) - Kubeapps helm chart hub by Bitnami

Application repositories
------------------------
These usually hold a single chart or a group of connected charts. Can be more up to date than the mainstream Kubernetes repos.

* [Gitlab Omnibus](https://charts.gitlab.io) - an All-In-One chart for deploying Gitlab in Kubernetes
* [Gitlab Cloud-native](https://helm.gitlab.io/) - a fresh start for Gitlab Kubernetes deployment, services are now split into their own containers
* [Jupyterhub and Binderhub](https://jupyterhub.github.io/helm-chart/) - charts for deploying services to run Jupyter notebooks
* [VMware Harbor](https://github.com/vmware/harbor/tree/master/contrib/helm/harbor) - VMWare's solution for a container registry
* [OpenStack](https://github.com/openstack/openstack-helm) - various charts by the OpenStack project
* [Fn Project](https://github.com/fnproject/fn-helm) - Fn serverless platform charts
* [Lenses](https://github.com/Landoop/kafka-helm-charts) - charts for Lenses, Apache Kafka, Kafka Connect and other components for data streaming and data integration
* [Zalenium](https://github.com/zalando/zalenium/tree/master/docs/k8s/helm) - flexible and scalable container based Selenium Grid with video recording, live preview, basic auth & dashboard
* [Elasticsearch Fluentd Kibana](https://github.com/cdwv/efk-stack-helm) - chart to deploy a full EFK stack for Kubernetes monitoring
* [Eclipse Che](http://www.eclipse.org/che/docs/kubernetes-multi-user.html) - instructions to install the Eclipse Che from the Helm chart bundled with the app
* [Gravitee.io](https://github.com/gravitee-io/gravitee-kubernetes/tree/master/gravitee) - Helm chart for Gravitee.io API management platform
* [Bitwarden](https://github.com/cdwv/bitwarden-k8s) - Helm chart for deploying bitwarden-rs - unofficial Bitwarden-compatible server

Plugins
-------

* [Helm Diff](https://github.com/databus23/helm-diff) - A helm plugin that shows a diff explaining what a `helm upgrade` and `helm rollback` would change. It can also compare two separate revisions of the release.
* [Helm Env](https://github.com/adamreese/helm-env) - a helm plugin to show the environment variables available to a helm plugin.
* [Helm Last](https://github.com/adamreese/helm-last) - A helm plugin that shows the latest release interacted with. This is useful for chaining commands together like `helm status $(helm last)`.
* [Helm Local](https://github.com/adamreese/helm-local) - a helm plugin to run Tiller (helm 2's server-side component) as a local daemon.
* [Helm Nuke](https://github.com/adamreese/helm-nuke) - A helm plugin that deletes and purges all releases stored by Tiller.
* [Helm Secrets](https://github.com/futuresimple/helm-secrets) - A helm plugin to manage and store secrets safely
* [Helm Monitor](https://github.com/ContainerSolutions/helm-monitor) - Plugin to monitor a release and rollback based on Prometheus/ElasticSearch query
* [Helm S3](https://github.com/hypnoglow/helm-s3) - Helm plugin to fetch charts from S3

Tools, Extras
-------------
Helm-related tools
* [Keel.sh](https://keel.sh) - Continuous delivery for Kubernetes - enhances Helm with auto upgrades and other cool features
* [Helmfile](https://github.com/roboll/helmfile) - Helmfile is a declarative spec for deploying helm charts, supports flexible templating scenarios
* [Helmsman](https://github.com/Praqma/helmsman) - Helmsman provides a declarative way of installing charts, features terraform-like desired state file approach and security enhancements
* [Reckoner](https://github.com/reactiveops/reckoner) - Reckoner is a tool to simplify management and installation of multiple Helm chart releases
* [Monocular](https://github.com/helm/monocular) - A web-based application that enables the search and discovery of charts from multiple Helm Chart repositories
* [Ship](https://github.com/replicatedhq/ship) - A tool that makes it easy to watch and apply updates to Helm charts and integrates [Kustomize](https://kustomize.io) patches and overlays

Community
---------
Forums, discussion groups, SO tags.

* [Helm Slack](http://slack.k8s.io/) - #helm-users channel on Kubernetes Slack
* [StackOverflow Kubernetes-Helm](https://stackoverflow.com/questions/tagged/kubernetes-helm) - Stack Overflow threads tagged kubernetes-helm
* [StackOverflow Helm](https://stackoverflow.com/questions/tagged/helm) - Stack Overflow threads tagged Helm

Contributing
=======================================================================

Contributions are most welcome!

This list is just getting started, please contribute to make it super awesome.

Check out the [Contributing Guidelines](https://github.com/cdwv/awesome-helm/blob/master/CONTRIBUTING.md).


License
=======================================================================

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">awesome-helm</span> by <a xmlns:cc="http://creativecommons.org" href="https://codewave.eu" property="cc:attributionName" rel="cc:attributionURL">CodeWave</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

Maintainers
===========

[<img width="300" title="Codewave.eu" src="cdwv-logo-new.svg">](http://codewave.eu)

Project is currently maintained, in our spare time, by [codewave.eu](http://codewave.eu) and a growing number of Contributors!
