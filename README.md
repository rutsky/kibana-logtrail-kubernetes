Extends Kubernetes' Kibana [image](https://github.com/kubernetes/kubernetes/blob/1c2ea28/cluster/addons/fluentd-elasticsearch/kibana-image/Dockerfile)
by adding compatible version of [Logtrail](https://github.com/sivasamyk/logtrail/) plugin and it's configuration,
suitable for EFK stack on Kubernetes.

You can get automatically built image from Docker Hub using:

```
docker pull rutsky/kibana-logtrail-kubernetes:4.6.1-0.1.7-2
```
