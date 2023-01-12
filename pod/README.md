<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/jenkins-pipeline-kubes/blob/main/pod/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Pod Docker Image

The Dockerfile in this folder is used to build the pod that is used for the Jenkins Kubernetes pod workers.

* It's ubuntu based
* It has ruby installed
* It has the kubes tool installed

## Build Commands

    docker build -t gcr.io/boltops-learn/jenkins-worker .
    docker push gcr.io/boltops-learn/jenkins-worker
