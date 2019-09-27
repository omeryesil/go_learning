

setenv:
	GOPATH=$(shell pwd)
    export GOPATH

build:
	protoc -I. --go_out=plugins=grpc:. \
	  proto/consignment/consignment.proto
