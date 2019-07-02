#!/bin/bash

#delete container f5-demo-app-route
oc delete -f f5-demo-app-route-deployment.yaml -n myproject
oc delete -f f5-demo-app-route-service.yaml -n myproject
