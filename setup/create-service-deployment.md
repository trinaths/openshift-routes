#!/bin/bash

#create container f5-demo-app-route
oc apply -f deployment.yaml -n f5demo
oc apply -f service.yaml -n f5demo
