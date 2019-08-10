# cloud-native-postgres
postgresql installation on docker, kubernetes and openshift

### postgres deployment on kubernetes
create persistent volume and claim
```
kubectl apply -f https://raw.githubusercontent.com/koseburak/cloud-native-postgres/master/kubernetes/postgres-persistentvolume.yaml
```
create node port service
```
kubectl apply -f https://raw.githubusercontent.com/koseburak/cloud-native-postgres/master/kubernetes/postgres-service.yaml
```
create config map
```
kubectl apply -f https://raw.githubusercontent.com/koseburak/cloud-native-postgres/master/kubernetes/postgres-configmap.yaml
```
create deployment
```
kubectl apply -f https://raw.githubusercontent.com/koseburak/cloud-native-postgres/master/kubernetes/postgres-deployment.yaml
```
