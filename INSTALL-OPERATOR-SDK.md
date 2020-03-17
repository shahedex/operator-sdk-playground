# Installing Operator SDK on Ubuntu

> This install requires Go 1.13

```bash
$ go get -d github.com/operator-framework/operator-sdk
```

```bash
$ cd $GOPATH/src/github.com/operator-framework/operator-sdk
```

```bash
$ git checkout master
```

```bash
$ make tidy
```

```bash
$ make install
```
