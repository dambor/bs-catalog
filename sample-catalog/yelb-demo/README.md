# Project Star Backstage - Demo App

We've provided a demo application catalog that corresponds to a demostrate application (with all the appropriate compnent labels). We recommend you clone the repo locally and customize the yelb application file to match your K8s cluster's capabilities.

## Application
[https://gitlab.eng.vmware.com/project-star/pstar-backstage-poc/-/blob/master/demo-app/yelb/yelb-k8s-loadbalancer.yaml](https://gitlab.eng.vmware.com/project-star/pstar-backstage-poc/-/blob/master/demo-app/yelb/yelb-k8s-loadbalancer.yaml) - This provides the application itself and assumes you have access to the corporate harbor repo (which we use as a image cache to avoid Docker Hub rate limiting) as well as it assumes you have a LoadBalancer.

## Catalog
We've provided the structure for a demonstrate catalog [here](https://gitlab.eng.vmware.com/project-star/pstar-backstage-poc/-/tree/master/demo-app/yelb-app-catalog). You're welcome to refer to ours (using the requisite GITLAB_TOKEN) directly or you can locate it on your own Git repo and refer to it there in your app-config.yaml file.


[Yelb leveraged from the this repo](https://github.com/mreferre/yelb/tree/master/deployments/platformdeployment/Kubernetes/yaml)
