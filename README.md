### PERHATIAN

- Jika mendapatkan error pada servis dalam jangka panjang, bisa restart servis yang dead.

### INSTALL SCRIPT 
<pre><code>apt install -y wget screen && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/ZvnStores/scupdate/main/main.sh && chmod +x main.sh && screen -S install ./main.sh</code></pre>

### UPDATE SCRIPT
<pre><code>wget https://raw.githubusercontent.com/ZvnStores/scupdate/main/update.sh && chmod +x update.sh && ./update.sh</code></pre>

### TESTED ON OS 
- UBUNTU 20.04.05
- DEBIAN 10

### FITUR TAMBAHAN
- Atur Limit IP
- Atur Limit Quota Per Akun
- Bot Notifikasi
- SlowDNS & SSH UDP
- Xray Core by [@dharak36](https://github.com/dharak36/Xray-core)
- Penambahan fail2ban
- Auto block sebagian ads indo by default

### PORT INFO
```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 80
- SSH UDP 1-65535
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```

BY: ZheeVPN ⚡
