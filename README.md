# Voltix TSS Library

Note: this repository is currently called `mobile-tss-lib` but will be renamed to a generic Voltix library in the future.

## Generate mobile bindings

```bash
# after I run `go mod tidy` , I will have to download mobile bind library again , otherwise gomobile command won't run
go get golang.org/x/mobile/bind
gomobile bind -v -target=ios,macos,iossimulator -tags=ios,macos,iossimulator github.com/voltix-vault/mobile-tss-lib/tss
```
