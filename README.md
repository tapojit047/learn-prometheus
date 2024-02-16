# learn-promethus
- Install Promethus:
```bash
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
helm install [RELEASE_NAME] prometheus-community/kube-prometheus-stack
```

- Link: [kube-prometheus-stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack)

- [Promethus Helm Carts](https://github.com/prometheus-community/helm-charts/tree/main/charts)
- [Druid-Exporter](https://github.com/opstree/druid-exporter)