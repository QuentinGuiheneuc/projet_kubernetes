# Projet Kubernetes

- Le group est conposer de LAFFONT Edouard,
  FAGET Corentin, GUIHENEUC Quentin 

1 - NAMESPACE

prod.
    requests.cpu: "1"
    requests.memory: 1Gi
    limits.cpu: "2"
    limits.memory: 4Gi 

Environnement de prod

dev.
    requests.cpu: "1"
    requests.memory: 1Gi
    limits.cpu: "2"
    limits.memory: 4Gi 

Environnement de dev pour test

client.
    requests.cpu: "1"
    requests.memory: 1Gi
    limits.cpu: "2"
    limits.memory: 2Gi

Environement client

system.
    requests.cpu: "1"
    requests.memory: 1Gi
    limits.cpu: "4"
    limits.memory: 8Gi

System (bdd - secu - etc)

