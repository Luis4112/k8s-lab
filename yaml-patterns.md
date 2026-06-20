## Pod

apiVersion: v1
kind: Pod
metadata:
  name:
spec:
  containers:
  - name:
    image:

## Deployment
apiVersion: apps/v1
kind: Deployment
metadata:
  name:
spec:
  replicas:2
  selector:
    matchLabels:
      app:
  template:
    metadata:
      labels:
        app:
    spec:
      containers:
      - name:
        image:


## Service

apiVersion: v1 
kind: Service
metadata:
  name:
spec:
  selector:
    app:
    ports:
    - port:
      targetPort:
    type:

