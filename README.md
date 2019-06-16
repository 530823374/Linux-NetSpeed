wget "https://github.com/530823374/Linux-NetSpeed/raw/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

部分如果提示连接不上github。可以先安装
yum install net-tools -y  或者 apt-get install net-tools -y

如果没有wget，比如搬瓦工vps，可以先安装wget

yum -y install wget

执行如何提示证书错误的话

yum -y install ca-certificates
或者

apt-get -y install ca-certificates
