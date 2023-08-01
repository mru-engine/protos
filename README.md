# protos

This repository contains protocol buffer files for Mru Engine.

## How to use?

You can integrate your golang project with this API, by installing this go modules:
```shell
$ go get buf.build/gen/go/mrucznik/mru-engine/connectrpc/go@latest
$ go get buf.build/gen/go/mrucznik/mru-engine/bufbuild/connect-go@latest
```

## Developing

You would probably need this tools, to develop this codebase:
```shell
$ go install github.com/bufbuild/buf/cmd/buf@latest
$ go install github.com/fullstorydev/grpcurl/cmd/grpcurl@latest
$ go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
$ go install github.com/bufbuild/connect-go/cmd/protoc-gen-connect-go@latest
```

## buf.build integration

After changing protobuf files, push them to buf.build with:
```shell
buf push
```
