# SSR-script

SSR-script is a backup tutorial for the auto installation of the shadowsocks server.

## Usage

在实例上生成SSH-KEY
'ssh-keygen -o'
添加到github账号SSH中
[在实例上生成SSH-KEY](https://git-scm.com/book/zh/v2/%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84-Git-%E7%94%9F%E6%88%90-SSH-%E5%85%AC%E9%92%A5)

```shell
git clone git@github.com:JiangnanShan97/SSR-script.git
cd SSR-script
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```
选择安装shadowsocks-libev (4)；设置密码、端口；安装simple-obfs，采用http混淆

## AWS

AWS provides a 12 month free trail which includes cloud server service.

Create a EC2 instance and install ssr.

Make sure to add inbound port for the ssr listening port.

Here is how: Instances > \<server name\> > Security > Security groups > Inbound rules > Edit inbound rules > Add rule \\
	type: TCP	port: \<corresponding ssr port\>	source: 0.0.0.0/0

## Digital Oceean



