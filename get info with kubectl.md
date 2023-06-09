## показываеют всю информацию про текущий кластер
```
kubectl get all
```

## сетевые адреса управляющего кластера
```
kubectl cluster-info
```

## Вывести все поддерживаемые типы ресурсов, включая API-группу, флаг namespaced (организован ли ресурс в пространство имён или нет) и Kind
```
kubectl api-resources
```

## показать объединённые настройки kubeconfig
```
kubectl config view
```

## показать список контекстов
```
kubectl config get-contexts
```

## Вывести все сервисы в пространстве имён
```
kubectl get services
```

## Вывести все ноды во всех пространств имён
```
kubectl get nods --all-namespaces
```

## Вывести все поды во всех пространств имён
```
kubectl get pods --all-namespaces
```

## Вывести постоянные тома (PersistentVolumes)
```
kubectl get pv
```

## Показать метки всех подов (или любого другого объекта Kubernetes, которым можно прикреплять метки)
```
kubectl get pods --show-labels
```

## Проверить содержимое объекта
```
kubectl describe <>
```

## получить список событий
```
kubectl get events
```

## Вывод логов в поде <pod-name> в режиме реального времени. Это похоже на команду 'tail -f' Linux.
```
kubectl logs -f <pod-name>
```
