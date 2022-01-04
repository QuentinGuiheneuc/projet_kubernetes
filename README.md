# Projet Kubernetes

- Le group est conposer de LAFFONT Edouard,
  FAGET Corentin, GUIHENEUC Quentin

## NAMESPACE

### Prod

- Environnement de prod.
  - requests.cpu: "1"
  - requests.memory: 1Gi
  - limits.cpu: "2"
  - limits.memory: 4Gi

### Dev

- Environnement de dev pour test.
  - requests.cpu: "1"
  - requests.memory: 1Gi
  - limits.cpu: "2"
  - limits.memory: 4Gi

### Client

- Environement client.
  - requests.cpu: "1"
  - requests.memory: 1Gi
  - limits.cpu: "2"
  - limits.memory: 2Gi

### System

- System (bdd - etc)
  - requests.cpu: "1"
  - requests.memory: 1Gi
  - limits.cpu: "4"
  - limits.memory: 8Gi
