```bash
kubectl create namespace grafana
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanapvc.yaml
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanadeployment.yaml
```

```bash
kubectl apply -f https://raw.githubusercontent.com/cfoos/Grafana/main/grafanaservice.yaml
```
