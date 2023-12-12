# `Install Script By Bayu`

<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/bayuvpn/free7/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh</pre></code>

# `FixSSH`
<pre><code>wget -q -O fix "https://raw.githubusercontent.com/xsm-syn/fix/main/ws-700.sh" && bash fix</pre></code>

# `Manual Update`
<pre><code>wget https://raw.githubusercontent.com/bayuvpn/free7/main/updatemenu.sh && chmod +x updatemenu.sh && ./updatemenu.sh</pre></code>

# `Update Backup`
<pre><code>wget https://raw.githubusercontent.com/bayuvpn/free7/main/backup/set-br.sh && chmod +x set-br.sh && ./set-br.sh</pre></code>

### WORK DI OS
```
- UBUNTU 20.04.05
- DEBIAN 10 ( Disarankan )

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```

### `WARNING !`
```
Jika Mendapatkan Status Service Off
Silahkan Restart Service.
Jika Statsus Service Masih Off
Silahkan Reboot vps kalian
```
