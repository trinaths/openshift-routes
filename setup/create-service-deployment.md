#!/bin/bash

#create container f5-demo-app-route
oc apply -f f5-demo-app-route-deployment.yaml -n myproject
oc apply -f f5-demo-app-route-service.yaml -n myproject
