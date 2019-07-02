#!/bin/bash

#create container f5-demo-app-route
oc apply -f deployment.yaml -n openshift
oc apply -f service.yaml -n openshift
