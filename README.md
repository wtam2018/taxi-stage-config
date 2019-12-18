# Deployment configuration for the staging environment

## About
This repository contains the kustomzisation overlays to deploy the [taxi application](https://github.com/sbose78/taxi)

## Why
The `stage` configuration repository for the [taxi application](https://github.com/sbose78/taxi) is used for maintaining the incremental deployment configuration ( 'manifests' ), specific to the `stage` environment.

## Pipelines
The [pipelines](../pipelines) that power the CI jobs for this repository have been defined as Tekton Tasks & Tekton Pipeline definitions.

### CI
The CI pipeline validates changes to the [kustomize'd deployment manifests](../deployment) 

### CD
The CD pipeline deploys the kustomize'd kubernetes manifests of the `taxi` app to the `stage` environment.

### Testing

This is a test commit.
