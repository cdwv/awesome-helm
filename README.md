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
* [How to create your first helm chart](https://docs.vmware.com/en/VMware-Tanzu-Application-Catalog/services/tutorials/GUID-create-first-helm-chart-index.html) - Bitnami guide on authoring your first chart
* [Best Practices Guide](https://helm.sh/docs/chart_best_practices/) - Best practices for creating charts
* [Chart Template Developer's Guide](https://helm.sh/docs/chart_template_guide/) - Official Helm guide on Chart Templating
* [v2 to v3 Migration](https://helm.sh/docs/topics/v2_v3_migration/) - Guide on migrating Helm v2 to v3

Repositories / hubs
-------------------
* [Kubernetes Helm charts stable repo](https://github.com/helm/charts/tree/master/stable)
* [Artifact Hub](https://artifacthub.io/) - Official Helm Artifactory Hub

## 3rd party repositories / hubs

* [Cloudsmith](https://cloudsmith.com/product/formats/helm-chart-repository) - A fully managed package management SaaS, with first-class support for public and private Kubernetes registries.
* [Kubeapps](https://kubeapps.dev/docs/latest/tutorials/managing-package-repositories/) - Kubeapps helm chart hub by Bitnami
* [JFrog](https://jfrog.com/integration/helm-repository/) - An enterprise-ready repository management for Helm charts

Application repositories
------------------------
These usually hold a single chart or a group of connected charts. Can be more up to date than the mainstream Kubernetes repos.

* [ArgoCD](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd) - Helm Chart for a declarative, GitOps continuous delivery tool for Kubernetes
* [FluxCD](https://github.com/fluxcd-community/helm-charts) - Community maintained Helm charts for Flux
* [Gitlab Omnibus](https://gitlab.com/gitlab-org/charts/gitlab) - an All-In-One chart for deploying Gitlab in Kubernetes
* [Jupyterhub and Binderhub](https://jupyterhub.github.io/helm-chart/) - charts for deploying services to run Jupyter notebooks
* [Harbor](https://github.com/goharbor/harbor-helm) - Harbor is a container and Helm registry with built-in security
* [OpenStack](https://github.com/openstack/openstack-helm) - various charts by the OpenStack project
* [Fn Project](https://github.com/fnproject/fn-helm) - Fn serverless platform charts
* [Mocktail](https://github.com/Huseyinnurbaki/mocktail) - Helm chart for deploying the free, tiny mock api server Mocktail

Plugins
-------

* [Helm Dt](https://github.com/vmware-labs/distribution-tooling-for-helm) - Plugin that helps moving Helm charts across OCI registries.
* [helm-adopt](https://github.com/HamzaZo/helm-adopt) - A helm v3 plugin to adopt existing k8s resources into a new generated helm chart.
* [helm-chartsnap](https://github.com/jlandowner/helm-chartsnap) - Snapshot testing plugin for Helm charts.
* [Helm Diff](https://github.com/databus23/helm-diff) - Preview helm upgrade as a coloured diff
* [Helm Dashboard](https://github.com/komodorio/helm-dashboard) - GUI for Helm, visualize releases and repositories, manifest diffs
* [helm-git](https://github.com/aslafy-z/helm-git) - Install charts and retrieve values files from your Git repositories
* [helm-k8comp](https://github.com/cststack/k8comp) - Plugin to create Helm Charts from hiera using k8comp
* [helm-mapkubeapis](https://github.com/helm/helm-mapkubeapis) - Update helm release metadata to replace deprecated or removed Kubernetes APIs
* [helm-monitor](https://github.com/ContainerSolutions/helm-monitor) - Plugin to monitor a release and rollback based on Prometheus/ElasticSearch query
* [helm-release-plugin](https://github.com/JovianX/helm-release-plugin) - Plugin for Release management, Update release values, pulls(re-creates) helm Charts from deployed releases, set helm release TTL.
* [helm-s3](https://github.com/hypnoglow/helm-s3) - Helm plugin that allows to use AWS S3 as a [private] chart repository
* [helm-secrets](https://github.com/jkroepke/helm-secrets) - Plugin to manage and store secrets safely (based on sops)
* [helm-sigstore](https://github.com/sigstore/helm-sigstore) - Plugin for Helm to integrate the sigstore ecosystem. Search, upload and verify signed Helm charts.
* [helm-tanka](https://github.com/Duologic/helm-tanka) - A Helm plugin for rendering Tanka/Jsonnet inside Helm charts.
* [hc-unit](https://github.com/xchapter7x/hcunit) - Plugin for unit testing charts locally using OPA (Open Policy Agent) & Rego
* [helm-unittest](https://github.com/quintush/helm-unittest) - Plugin for unit testing chart locally with YAML
* [helm-val](https://github.com/HamzaZo/helm-val) - A plugin to get values from a previous release.
* [helm-external-val](https://github.com/kuuji/helm-external-val) - A plugin that fetches helm values from external sources (configMaps, Secrets, etc.)
* [helm-images](https://github.com/nikhilsbhat/helm-images) - Helm plugin to fetch all possible images from the chart before deployment or from a deployed release
* [helm-drift](https://github.com/nikhilsbhat/helm-drift) - Helm plugin that identifies the configuration that has drifted from the Helm chart
* [Helm Last](https://github.com/adamreese/helm-last) - Plugin that shows the latest release interacted with. This is useful for chaining commands together like `helm status $(helm last)`
* [Helm Local](https://github.com/adamreese/helm-local) - Plugin to run Tiller (helm 2's server-side component) as a local daemon.
* [Helm Nuke](https://github.com/adamreese/helm-nuke) - Plugin that deletes and purges all releases stored by Tiller.
* [Helm Starter](https://github.com/salesforce/helm-starter) - Plugin that simplifies working with helm chart starter packs.
* [Helm GCS](https://github.com/hayorov/helm-gcs) - Plugin that manages chart repos on Google Cloud Storage privately.
* [Helm GitHub](https://github.com/web-seven/helm-github) - Plugin that detects and install Helm Charts from GitHub Public/Private Repository Releases.
* [Helm Schema](https://github.com/dadav/helm-schema) - Auto-generate jsonschema files for helm charts.
* [Helm Schema Gen](https://github.com/karuppiah7890/helm-schema-gen) - So that you don't have to write `values.schema.json` by hand from scratch for your Helm 3 charts 
* [Helm Datree](https://github.com/datreeio/helm-datree) - Plugin to prevent Kubernetes misconfigurations by ensuring that Helm charts follow best practices as well as your organization’s policies
* [Helm Teller](https://github.com/SpectralOps/helm-teller) - Plugin that allows you to manage deployment configuration and secrets from multiple providers securely
* [Helm Release](https://github.com/JovianX/helm-release-plugin) - Plugin that allows running operations on Helm releases (deployed Helm charts)
* [Helm Compose](https://github.com/seacrew/helm-compose) - Plugin that allows coupled multi release handling of one or many charts. With full configuration-as-code capabilities in a single yaml file similar to docker-compose.

Tools & Extras
-------------
Helm-related tools

* [Helmfile](https://github.com/helmfile/helmfile) - Helmfile is a declarative spec for deploying helm charts, supports flexible templating scenarios
* [Helm-Controller](https://github.com/fluxcd/helm-controller) - Kuberenetes operator to declaratively manage Helm chart releases
* [Helmwave](https://docs.helmwave.app/0.38.x/intro/) - Helm-native tool to help deploying helm charts faster in mutiple environments
* [Captain](https://github.com/alauda/captain) - Contoller to watch HelmRequest CRD(Which defines how to install Helm charts), process them, and sync their states
* [ChartMuseum](https://chartmuseum.com/) - ChartMuseum is an open-source, easy to deploy, Helm Chart Repository server.
* [Helmify](https://github.com/arttor/helmify) - Generates a Helm chart from Kubernetes yamls
* [chart-testing](https://github.com/helm/chart-testing) - CT is the tool for linting and testing Helm charts.
* [Helmsman](https://github.com/Praqma/helmsman) - Helmsman provides a declarative way of installing charts, features terraform-like desired state file approach and security enhancements
* [Reckoner](https://github.com/FairwindsOps/reckoner) - Reckoner is a tool to simplify management and installation of multiple Helm chart releases
* [Keel.sh](https://keel.sh) - Continuous delivery for Kubernetes - enhances Helm with auto upgrades and other cool features
* [Chart Releaser](https://github.com/helm/chart-releaser) - Helps Turn GitHub Repositories into Helm Chart Repositories
* [Helm Docs](https://github.com/norwoodj/helm-docs) - Auto-generates documentation from helm charts into markdown files
* [Readme Generator](https://github.com/bitnami-labs/readme-generator-for-helm) - Autogenerate Helm Charts READMEs' tables based on values YAML file metadata.
* [Chart Viewer](https://github.com/ecojuntak/chart-viewer) - Helps you inspect and compare chart template and also rendered manifest
* [werf](https://werf.io/) - A CLI tool for implementing CI/CD best practices using an extended version of Helm under the hood for deployment


Community
---------
Forums, discussion groups, SO tags.

* [Helm Slack](https://kubernetes.slack.com/messages/C0NH30761) - #helm-users channel on Kubernetes Slack
* [Mailing list](https://lists.cncf.io/g/cncf-helm/topics) - Helm Mailing List by CNCF
* [StackOverflow Helm](https://stackoverflow.com/questions/tagged/helm) - Stack Overflow threads tagged Helm

Contributing
=======================================================================

Contributions are most welcome!

Please contribute to make it super awesome.

Check out the [Contributing Guidelines](https://github.com/cdwv/awesome-helm/blob/master/CONTRIBUTING.md).


License
=======================================================================

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">awesome-helm</span> by <a xmlns:cc="http://creativecommons.org" href="https://codewave.eu" property="cc:attributionName" rel="cc:attributionURL">CodeWave</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

Maintainers
===========

[<img width="300" title="Codewave.eu" src="cdwv-logo-new.svg">](https://codewave.eu)

Project is currently maintained, in our spare time, by [codewave.eu](https://codewave.eu) and a growing number of Contributors!
