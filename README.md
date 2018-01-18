# MyVPN
apt-get install python-pip

pip install shadowsocks

ssserver -p 8000 -k password -m rc4-md5 -d start

or

ssserver -c /etc/shadowsocks.json -d start
