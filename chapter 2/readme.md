# how to get replica sets command :
```
kubectl get replicaset
```
# What is the image used to create the pods in the replicaset?
```
kubectl describe replicaset
```
# How many pods are ready in a replicaset?
```
kubectl get replicaset
```

# Why do you think the PODs are not ready?
``
Run the command:  "kubectl describe pods" 
and look at under the Events section.
``
# How to delete a pod ?

```
kubectl delete pod podname
```
