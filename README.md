

# hyperledger doc

## fabric doc web
https://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html


## fabric arch 
https://blog.csdn.net/russell_tao/article/details/80459698

## hyperledger arch introduce
https://blog.csdn.net/weixin_41545330/article/details/79480069

##  hyperledger doc
http://hyperledger-fabric.readthedocs.io/en/release-1.2/whatis.html

##超级账号入门

http://www.ethchinese.com/?p=216


# install

## centos 

a install docker
  https://www.runoob.com/docker/centos-docker-install.html
  docker --version

b install docker-compose
  sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

  sudo chmod +x /usr/local/bin/docker-compose

  docker-compose --version

c Go version 1.12.x is required.

d fabric SDK for Node.js, version 8 is supported from 8.9.4 and higher. Node.js version 10 is supported from 10.15.3 and higher

e wget https://raw.githubusercontent.com/hyperledger/fabric/master/scripts/bootstrap.sh
  执行上边的内容，会搭建环境,下载bin 和sample代码

# run example

cd fabric-samples/fist-network
./byfn.sh generate
./byfn.sh up


 

