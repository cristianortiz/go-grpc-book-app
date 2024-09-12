# go-grpc-book-app
grpc and golang based app
## Project folder structure
``` ultree 
├── cmd/
│   └── main.go
├── configs/
├── deploy/
├── go.mod
├── internal/
├── main.go
├── README.md
├── scritps/
└── test/
```  

- cmd : a kind of hub or entry point of the codebase like main files, if the codebase consist of several apps create subfolder for every app
- internal : dedicated to housing code for internal use only, like libraries that should not be imported or used by external apps or libraries