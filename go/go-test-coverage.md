# Go Test Coverage

Generate Go test coverage report

1. Using command line

```shell
go test -v -coverprofile cover.out ./YOUR_CODE_FOLDER/...
go tool cover -html cover.out -o cover.html
open cover.html
```

Copy from [Stack Overflow](https://stackoverflow.com/a/51634670)

2. Using Goland

- Click `Run with Coverage` button on the top of the test file.
- Then you can see the coverage report in the `Coverage` window.
