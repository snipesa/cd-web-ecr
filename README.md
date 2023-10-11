# cd-web-ecr
CD repo using Argo CD for kubernetes deployment

This is a continuous deployment for a kubernetes cluster. The tool used for continuous deployment is Argo-CD

The repo is subdivided into  directories:
- argocd
- eks-cluster
- manifest-files

## argocd

This folder contains 2 files.
The first is the installation file to install argo-cd into your kubernetes cluster.
The second file is an application.yaml file to install or link the state of your git-repo or helm chart to your kubernetes cluser

## eks-cluster

This entails a simple config.yaml file to create an eks cluster. This is if you dont already have an available kubernetes cluster running.

## manifest files

This folder contains the various manifest files for our kubernetes cluster