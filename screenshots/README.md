# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job

## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```

![deployments](https://user-images.githubusercontent.com/109697571/205722382-5e3aaf38-9399-459f-8da2-a3592d6e9921.PNG)
![describe svc](https://user-images.githubusercontent.com/109697571/205722392-f24a2212-e077-45d6-8c4d-a611ddd1c76c.PNG)
![dockerhub](https://user-images.githubusercontent.com/109697571/205722396-6bd61075-c71b-4370-a215-488d224e85dc.PNG)
![HPA](https://user-images.githubusercontent.com/109697571/205722403-123655eb-471b-4d30-8f78-ed5b041d02e0.PNG)
![logs](https://user-images.githubusercontent.com/109697571/205722422-f049a3f2-f2a7-4472-a256-aa1930ebe7f7.PNG)
![pods](https://user-images.githubusercontent.com/109697571/205722426-bc80b4e4-9a8a-4419-abe8-f702065f457d.PNG)
![replicas](https://user-images.githubusercontent.com/109697571/205722435-728d2ed0-2083-44dc-9ddc-33c95d216269.PNG)
![SVC](https://user-images.githubusercontent.com/109697571/205722440-946bdee0-15be-42ed-99c1-5f6bb50812e1.PNG)
![travis ci](https://user-images.githubusercontent.com/109697571/205722445-d3a68c1e-585c-45f3-8d88-f5771869d40d.PNG)

![screenshots links inside readme](https://user-images.githubusercontent.com/109697571/205726422-36b06f19-fc3a-4f3c-8084-349ac144f8f1.PNG)

