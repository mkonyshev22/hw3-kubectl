- Запуск приложения
```bash
kubectl apply -f .
```

- Остановка приложения
```bash
kubectl delete -f .
```

Вспомогательные команды
- Запуск minikube
```bash
minikube start
```
- Остановка minikube
```bash
minikube delete
```
- Запуск tunnel
```bash
minikube tunnel
```
- Остановка tunnel
```
ctrl-c
```
- Список и статус дополнений minikube
```bash
minikube addons list
```
- Запуск ingress
```bash
minikube addons enable ingress
```

