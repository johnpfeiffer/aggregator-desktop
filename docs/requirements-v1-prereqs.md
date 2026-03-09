# Goal

basic foundation for the app

## Steps

*the assumption here is MacOS...*

- Golang: https://go.dev/doc/install
- - `brew install golang`
- - `which go; go version`
- - `echo 'export PATH="$PATH:$(go env GOPATH)/bin"' >> ~/.zshrc`

*because "GOPATH/bin" is the default destination for `go install` - now making tools runnable*

- NPM: https://nodejs.org/en/download/
- - `brew install node`
- - `which npm; npm --version; node --version` 

Wails framework: https://wails.io/docs/gettingstarted/installation/

`go install github.com/wailsapp/wails/v2/cmd/wails@latest`

`ls $(go env GOPATH)/bin`

`wails version`


## React with Typescript

`wails init -n aggregator-desktop -t react-ts`

```
cd aggregator-desktop
rm README.md
mv * ..
```

**golang apps generally have go.mod and main.go at the root level**

