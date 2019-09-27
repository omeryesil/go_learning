# go_learning

I followed the mostly the same steps from an article on ewanvalentine.io site (see the Refrence) to learn how to develop micro services by using golang.  

Reference: https://ewanvalentine.io/microservices-in-golang-part-1/

- Will use protobuf (https://developers.google.com/protocol-buffers) and gRPC (https://grpc.io/faq/) as the protocol

- Services to be created 
  - consignments
  - inventory
  - users
  - authentication
  - roles
  - vessels

For learning purpose, we will have all the services located under the same repo. However, the recommended approach for microservices is to have separete/independent repo for each service.

- Tech Stack
  - golang
  - mongodb
  - grpc
  - docker
  - Kubernetes (any: AKS, EKS, GCK, Minikube..)
  - CircleCI
  - Terraform
  - go-micro

## Prerequisities

- Install gRPC and protobuf (https://grpc.io/docs/quickstart/go/)
  - Or to install protobuf follow this, which puts the protoc under /usr/local/bin so that we don't need to specifically add its path to PATH environment variable
  ```shell
  PROTOC_ZIP=protoc-3.9.2-osx-x86_64.zip
  curl -OL https://github.com/protocolbuffers/protobuf/releases/download/v3.9.2/$PROTOC_ZIP
  sudo unzip -o $PROTOC_ZIP -d /usr/local bin/protoc
  sudo unzip -o $PROTOC_ZIP -d /usr/local include/*
  rm -f $PROTOC_ZIP
  ```

- Install Golang (if you don't have already)
- Install the following libraries
  ```shell
  go get -u google.golang.org/grpc
  go get -u github.com/golang/protobuf/protoc-gen-go
  ```

## Services 

### Consignment Service 




  

  
