# cloud-native-postgres
postgresql installation on docker, kubernetes and openshift

### postgres deployment on kubernetes
1. create persistent volume
'''
kubectl apply -f https://github.com/koseburak/cloud-native-postgres/blob/master/kubernetes/postgres-persistentvolume.yaml
'''