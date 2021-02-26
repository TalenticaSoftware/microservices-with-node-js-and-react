# microservices-with-node-js-and-react


$ cd skaffold

$ docker login
Need to update my docker image name webmakaka/grider-ms-app1*** to your in scripts from skaffold and k8s folders.

$ skaffold dev

$ kubectl get pods
NAME                              READY   STATUS    RESTARTS   AGE
client-depl-99b7fcdcb-jhttp       1/1     Running   0          3m22s
comments-depl-69578db79c-jzdnh    1/1     Running   0          3m22s
event-bus-depl-7c5b75b7f4-m5qw6   1/1     Running   0          3m22s
moderation-depl-d7b49bfbc-cgl2l   1/1     Running   0          3m22s
posts-depl-78647cffd4-7gtzx       1/1     Running   0          3m22s
query-depl-656f9b6b58-bv7g7       1/1     Running   0          3m22s
