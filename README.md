# TestK8S

## Launch
```bash
kubectl apply -f app.yaml
chmod a+x && ./cmd_file
kubectl apply -f ingress.yaml
```

## Проблемки
Вроде как по guides все нормально описал, но так и не смог проверить 
правильно ли работает ingress. По проверке в k8s все сервисы работают 
исправно, но попытки проверить настроенные пути в ingress с помощью 
curl провалились с треском.
