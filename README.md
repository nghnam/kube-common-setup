## K8s common setup
This chart bootstraps and manages common configs on a Kubernetes cluster using the Helm package manager.

## Manage
- Namespace
- Quota
- Service Account
- Role
- Role Binding
- Cluster Role
- Cluster Role Binding
- Registry Secret 
- Isolate Network Policy

## Show templates
```
$ helm template .
```

## Run
- Install
```
$ helm install . --name common [--dry-run]
```

- Upgrade
```
$ helm upgrade common . [--dry-run]
```

- Rollback
```
$ helm rollback common <revision> [--dry-run]
```

# Author
Nam Hoang Nguyen <nguyen.h.nam.vn@gmail.com>

# License

See [LICENSE](https://github.com/nghnam/kube-common-setup/blob/master/LICENSE)