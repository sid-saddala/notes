````
wget https://storage.googleapis.com/golang/go1.7.3.linux-amd64.tar.gz
tar xvf go1.7.3.linux-amd64.tar.gz
sudo chown -R root:root ./go
sudo mv go /usr/local
vi ~/.bash_profile
  export GOPATH=$HOME/work
  export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin
go version
go env
````
