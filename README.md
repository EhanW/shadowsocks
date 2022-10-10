# shadowsocks

wget --no-check-certificate -O shadowsocks.sh https://github.com/EhanW/shadowsocks/blob/main/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
