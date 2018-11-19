



kubectl -n ffi run ubuntu --image amd64/ubuntu:16.04

kubectl -n ffi create -f ubuntu.yaml 

kubectl -n ffi get deployments.

kubectl -n ffi get po

kubectl -n ffi exec -it ubuntu -- /bin/bash
