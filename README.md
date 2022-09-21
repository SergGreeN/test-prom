### Clone repo

```
git clone https://github.com/SergGreeN/test-prom.git
```

### Build dependency

```
helm dependency build
```

### Install helm chart

```
helm install test1 . --namespace unitest --create-namespace --wait
```

