apt update -y && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt install -y lolcat wget bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/kenDevXD/0/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
 
