.DEFAULT_GOAL := build

.PHONY:fmt vet build 
fmt:
	go fmt ./...

vet: fmt
	go vet ./...

clean: vet
	go clean -cache -i

build: clean 
	go build
