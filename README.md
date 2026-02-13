Next => https://go.dev/doc/tutorial/call-module-code

.mod is to manage dependency, somewhat similar to package.json

```bash
cd hello
go run .

# this will automatically find missing package that is used in the code and install it 
go mod tidy
```

- Each module have it's own .mod to manage dependency