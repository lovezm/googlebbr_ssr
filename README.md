# googlebbr_ssr
google bbr + shadowsocksr backup<br>
#本处仅作备份 以免以后自己忘记如何安装

wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/YankeeBBR/master/bbr.sh && bash bbr.sh install
<br>如果脚本链接失效可以用上面的bbr.sh备份
<br>
#shadowsocksR<br>
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh<br>
chmod +x shadowsocksR.sh<br>
./shadowsocksR.sh 2>&1 | tee shadowsocksR.log<br>
