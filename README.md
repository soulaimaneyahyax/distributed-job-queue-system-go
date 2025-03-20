# distributed-job-queue-system-go

Go Concurrency - Distributed Job Queue System

run
```sh
go mod init distributed-job-queue-system-go
go run .
```

build
```sh
go build main.go && ./main
```

test
```sh
go test .
```

test race condition
```sh
go run -race .
go test -race .
```
