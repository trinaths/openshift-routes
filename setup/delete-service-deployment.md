#!/bin/bash

#delete container f5-demo-app-route
oc delete -f deployment.yaml -n openshift
oc delete -f service.yaml -n openshift
