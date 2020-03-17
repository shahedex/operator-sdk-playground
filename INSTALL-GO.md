# Install Go 1.13 in Ubuntu

```bash
sudo apt-get update
sudo apt-get -y upgrade
```

```bash
wget https://dl.google.com/go/go1.13.3.linux-amd64.tar.gz
```

```bash
sudo tar -xvf go1.13.3.linux-amd64.tar.gz
```

```bash
sudo mv go /usr/local
```

```bash
$ export GOROOT=/usr/local/go
$ export GOPATH=$HOME/go
$ export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```

Or, add them to ~/.profile to make the exports permanent.

Check the installed go version by running-

```bash
$ go version
```
