# Dummy ODH Application

A bare bones repository with minimal artifacts to create an ODH-managed application for testing

## Prerequisites
1. You are logged into an openshift cluster via `oc`
2. You have the Open Data Hub operator installed on the cluster
3. Your oc client is set to use your target namespace (via `oc project $PROJECTNAME`)

## Installation
Apply the Dummy App KfDef via:

```sh
oc apply -f dummy-app.kfdef.yaml
```
