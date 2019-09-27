# go_learning

I followed the exact steps from ewanvalentine.io site (see the Refrence) to learn how to develop micro services by using golang.  

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
- Install Golang (if you don't have already)
- Install the following libraries
  ```shell
  go get -u google.golang.org/grpc
  go get -u github.com/golang/protobuf/protoc-gen-go
  ```

## Services 

### Consignment Service 




  

  
