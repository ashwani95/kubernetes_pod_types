# Description
**Kubernetes** is an open-source container-orchestration system which is used for automating deployment,scaling and management of containerized application.

A **Pod** is the basic building block of Kubernetes–the smallest and simplest unit in the Kubernetes object model that you create or deploy. A Pod represents a running process on your cluster.
Pods can be created and deployed in a number of different ways depending on the usecase. 

This repository contains scripts for running different type of Pods viz :
- [Daemonset](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
- [Deployment](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
- [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
- [Jobs](https://kubernetes.io/docs/concepts/workloads/controllers/jobs-run-to-completion/)
- [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
- [Pods](https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/)
- [Replica Sets](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/)
- [Replication Controller](https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller/)
- [Services](https://kubernetes.io/docs/concepts/services-networking/service/)
- [Stateful Set](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)


**Note** : The above pod types are as per the latest Kubernetes Release v1.12. Older kubernetes versions might not support some of these pod types. Please refer [Kubernetes Documentation](https://kubernetes.io/docs/home/?path=browse) for more details.
