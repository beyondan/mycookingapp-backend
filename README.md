# MyCookingApp Backend (Go, Echo)
# Getting started
1. Install [Golang](https://golang.org/dl/)
2. Set `$GOBIN`. This is where all Go modules will be installed:
```bash
go env -w GOBIN=$HOME/go/bin
```
3. From this folder, install (compile) the module. As defined in [go.mod](./go.mod), the install command will compile an executable named `backend` in your `$GOBIN`.
or
```bash
go install .
```

4. Add `$GOBIN` to your `$PATH` so that your terminal/command prompt recognizes the executable you just built.

- For Mac:
```bash
export PATH=$PATH:$(go env GOBIN)
```
- For Windows:
```dos
setx PATH "%PATH%;%USERPROFILE%\go\bin"
```

4. Run the executable. 
```bash
backend
```
