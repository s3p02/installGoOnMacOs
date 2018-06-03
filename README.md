# installGoOnMacOs
notes for installing go on Mac using brew


```
mkdir $HOME/Go
```


```
mkdir -p $HOME/Go/src/github.com/user
```


```
export GOPATH=$HOME/Go
```


```
export GOROOT=/usr/local/opt/go/libexec
```


```
export PATH=$PATH:$GOPATH/bin
```


```
export PATH=$PATH:$GOROOT/bin
```


```
brew install go
```


```
go get golang.org/x/tools/cmd/godoc
```
