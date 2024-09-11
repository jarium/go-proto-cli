# Go Proto Cli
A tool for both generating .proto files and go codes from them (including http, grpc server codes).
```bash
go get github.com/jarium/go-proto-cli
go install github.com/jarium/go-proto-cli
``` 

### Init
```bash
go-proto-cli initiate
```

### Add Proto File
```bash
go-proto-cli add -name=example
go-proto-cli add -name=example -http=true #with http server
``` 

### Generate Go Code From Proto File
```bash
go-proto-cli generate -name=example
``` 