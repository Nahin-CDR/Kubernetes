# Kubernetes
Notes And Practice

বাংলা নোট এখানে পাবে 
https://appmaster.io/bn/blog/kubaarnetts-ki#kubernetes-span-klaasttaar-ki

# Create a new pod with the Nginx image command line :

```
kubectl run nginx --image=nginx
```

# Get all running pods command line :
```
kubectl get pods
```

# How to see description of new pods

```
kubectl describe pod newpods
```

# How to see on which nodes are my Pods placed on ? run this command :

```
kubectl get pods -o wide
```

# check how many container in an app

```
How many containers are part of the pod `webapp`?
run command :
kubectl describe pod webapp
```

# Delete a pod :

```
kubectl delete podname
```

# Create a new pod with the name `redis` and the image `redis123`.

```

kubectl run redis --image=redis123 --dry-run=client -o yaml > redis-definition.yaml

```

After that, using `kubectl create -f` command to create a resource from the manifest file :-


```
kubectl create -f redis-definition.yaml 
```

Verify the work by running `kubectl get` command :-

```
kubectl get pods
```

# If I want description of a running pod then the command will be 

```
kubectl describe pod podname
```

