Next =>
- https://go.dev/doc/code
- https://pkg.go.dev/github.com/gin-gonic/gin#section-readme
- https://go.dev/doc/effective_go

Done read
1. https://go.dev/doc/tutorial/call-module-code
2. https://go.dev/doc/tutorial/web-service-gin

.mod is to manage dependency, somewhat similar to package.json

```bash
cd hello
go run .

# this will automatically find missing package that is used in the code and install it
go mod tidy

```

- Each module have it's own .mod to manage dependency

# REST API

```bash
cd web-service-gin
go mod init example/web-service-gin

go get .
# Use a dot argument to mean “get dependencies for code in the current directory.
```