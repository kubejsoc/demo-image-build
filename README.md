# demo-image-build
Demo Image Build using k8s and kaniko

# Steps

1. Clone this repo to local
2. Make changes to `Dockerfile` if required.
3. make any changes you need in `www/index.html` 
4. push kaniko pod to k8s using `kubectl apply -f k8s/kaniko-pod.yaml` 
5. then monitor kaniko pod using `kubectl logs kaniko --follow`
