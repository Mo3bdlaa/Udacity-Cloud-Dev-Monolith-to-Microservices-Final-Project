# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed [ADDED]
<img src="1-Docker-Images.png" alt="Hello 👋" style="width:1000px;"/>
* GitHub repository’s settings showing your Travis webhook [ADDED]
<img src="2-Travis-Github.png" alt="Hello 👋" style="width:1000px;"/>
* Travis CI showing a successful build and deploy job  [ADDED]
<img src="3-Travis-CI-Successful-Jobs.png" alt="Hello 👋" style="width:1000px;"/>

## Kubernetes
* To verify Kubernetes pods are deployed properly  [ADDED]
```bash
kubectl get pods
```
<img src="4-Kubernetes-get-pods-deps-svc-hpa.png" alt="Hello 👋" style="width:1000px;"/>
* To verify Kubernetes services are properly set up  [ADDED]
```bash
kubectl describe services
```
<img src="5-Kubernetes-describe-Services.gif" alt="Hello 👋" style="width:1000px;"/>
* To verify that you have horizontal scaling set against CPU usage  [ADDED]
```bash
kubectl describe hpa
```
<img src="5-Kubernetes-hpa.gif" alt="Hello 👋" style="width:1000px;"/>
* To verify that you have set up logging with a backend application [ADDED]
```bash
kubectl logs {pod_name}
```
<img src="7.1-Backend-feed-and-user-logs.png" alt="Hello 👋" style="width:1000px;"/>
<img src="7.2-Reverse-Proxy-Logs.png" alt="Hello 👋" style="width:1000px;"/>
