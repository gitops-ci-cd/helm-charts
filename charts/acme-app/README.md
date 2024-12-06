# Acme App Helm Chart

## Usage

Install via [OCI-based registry](https://helm.sh/docs/topics/registries/) **(recommended)**:

```shell
helm pull oci://ghcr.io/gitops-ci-cd/charts/acme-app
helm install acme-app acme-app-[tag].tgz
```

Install via traditional [chart repository](https://helm.sh/docs/topics/chart_repository/):

```shell
helm install acme-app gitops-ci-cd/acme-app
```
