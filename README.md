# Rubik's little Kube on net

## Story

Ever since you helped your colleague's friend on how start with kubernetes, you also want to play with Minikube, because you don't want to be out of practice.

## What are you going to learn?

- How to deploy services to kubernetes
- How to make ingress for kubernetes pods
- What is a pod and ingress

## Tasks

1. Install test service to K8s and make ingress for them
    - Deploy Google's sample app is name Hello App
    - Check the Hello app web interface
    - Make a ingress yaml file and apply to the cluster
    - Open the previously configured domain

2. Deploy another app with same domain but specific path
    - Deploy Google's sample app is name Hello App with 2.0 version tag
    - Check the Hello app 2.0 web interface
    - Modify the existing ingress yaml file and add /v2 path point to the 2.0 app
    - Open the new configured domain path

## General requirements

None

## Hints

- You can make an ingress to domain path not just a domain
- You can deploy same app with different version

## Background materials

* <i class="far fa-book-open"></i> [Tutorial for Kubernetes ingress](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/)
* <i class="far fa-book-open"></i> [How to make fake domain in Local Machine](https://kb.leaseweb.com/products/hosting/web-hosting/adding-a-website-to-hosts-file-and-testing-it)
* <i class="far fa-book-open"></i> [Using a local domain name for testing](https://www.itenvoy.com/using-a-local-domain-name-for-testing/)
