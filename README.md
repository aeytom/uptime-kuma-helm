# uptime-kuma-helm

A simple kubernetes helm chart for [update-kuma](https://github.com/louislam/uptime-kuma)

`update-kuma` is a self-hosted monitoring tool like "Uptime Robot".

## Setup / Install

- Copy `values-example.yaml` to `values.local.yaml`
- Edit `values.local.yaml` to match your requirements
- install chart via `helm`

```sh
helm upgrade --install -n [NAMESPACE] -f values.local.yaml [RELEASENAME] ./uptime-kuma
```
