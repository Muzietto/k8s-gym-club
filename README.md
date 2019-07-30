# k8s-gym-club
Exercising with Kubernetes

```
# Luca's Version
#export KUBE_CONFIG_DEV=/home/developer/workspace/k8s-dev/kube_config/kubeconfig
#export KUBECONFIG=${KUBE_CONFIG_DEV}

# Marco's Version
export DOCKER_TLS_VERIFY="1"
export DOCKER_HOST="tcp://192.168.99.100:2376"
export DOCKER_CERT_PATH="/home/developer/.minikube/certs"
```

## Bypassing k8s office settings

- rename HOMEDIR/.docker
- rename HOMEDIR/.kube
- install minikube.exe and kubectl.exe in /usr/local/bin
- comment/uncomment lines in .bashrc
- exit the shell or execute the following commands _in each open shell_:
  - export KUBE_CONFIG_DEV=""
  - export KUBECONFIG=""

### Switching back to office settings
- rename HOMEDIR/.docker
- rename HOMEDIR/.kube
- rename minikube.exe and kubectl.exe in /usr/local/bin
- comment/uncomment lines in .bashrc
- exit the shell or execute the following commands _in each open shell_:
  - export DOCKER_CERT_PATH=""
  - export DOCKER_HOST=""
  - export DOCKER_TLS_VERIFY=""
