#!/bin/bash

#delete container f5-demo-app-route
oc delete -f deployment.yaml -n f5demo
oc delete -f service.yaml -n f5demo
