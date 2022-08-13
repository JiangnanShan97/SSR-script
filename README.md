# SSR-script

SSR-script is a backup tutorial for the auto installation of the shadowsocks server.

## Usage

```shell
git clone git@github.com:JiangnanShan97/SSR-script.git
cd SSR-script
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

```

## AWS

AWS provides a 12 month free trail which includes cloud server service.

Create a EC2 instance and install ssr.

Make sure to add inbound port for the ssr listening port.

Here is how: Instances > \<server name\> > Security > Security groups > Inbound rules > Edit inbound rules > Add rule \\
	type: TCP	port: \<corresponding ssr port\>	source: 0.0.0.0/0

## Digital Oceean



