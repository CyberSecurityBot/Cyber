# [cyberSecurity](https://telegram.me/CyberSecurityFAQ)
* **Install Bot**
`````sh
CyberSecurity`````





sudo apt-get update; sudo apt-get upgrade

sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv

reboot
========================================


wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz

tar zxpf luarocks-2.2.2.tar.gz
 
cd luarocks-2.2.2
 
./configure; sudo make bootstrap
 
sudo luarocks install luasocket
 
sudo luarocks install luasec
 
sudo luarocks install redis-lua
 
sudo luarocks install lua-term
 
sudo luarocks install serpent
 
sudo luarocks install dkjson
 
sudo luarocks install lanes
 
sudo luarocks install Lua-cURL
=======================================================
***************************************


cd $HOME && git clone https://github.com/CyberSecurityBot/Cyber.git && cd Cyber && chmod +x start.sh && ./start.sh install 

./start.sh

****************************************

cd $HOME && cd Cyber

killall screen

killall tmux

killall telegram-cli

tmux new-session -s script "bash steady.sh -t"

***************************************
