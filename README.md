# Practise Kubernetes

### Purpose:
The purpose of this project is just to practise some Kubernetes commands/functionality.  

The application and more information can be found in this [REPOSITORY](https://github.com/gdouglas7/zebra-unicorn-app)

### How to build and run:
1. Create the proxy  
    a. To run in Windows/OSx with Docker Desktop type: `kubectl apply -f .\proxy\ic-nginx-hn.yaml`  
    b. To run in Linux with Minikube or Microk8s type: `kubectl apply -f .\proxy\ic-nginx-lb.yaml`  
2. Create all other resources:
    `kubectl apply -f .`

### How to access the apps locally:
- For voting, you can access, [here](http://vote.127.0.0.1.nip.io/api/swagger-ui.html) and try the api `/api/vote`  

- For look at the result, you can access [here](http://result.127.0.0.1.nip.io/api/swagger-ui.html) and try the api `/api/result/votes`








