```sh
# 安装部署SSR
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

# Hostwinds 搭建 BBR 加速
wget –no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
```

```
Which Shadowsocks server you'd select:
1) Shadowsocks-Python
2) ShadowsocksR
3) Shadowsocks-Go
4) Shadowsocks-libev
Please enter a number (Default Shadowsocks-Python):2

You choose = ShadowsocksR

Please enter password for ShadowsocksR
(Default password: teddysun.com):tiankx1003

password = tiankx1003

Please enter a port for ShadowsocksR [1-65535]
(Default port: 9042):8098

port = 8098

Please select stream cipher for ShadowsocksR:
1) none
2) aes-256-cfb
3) aes-192-cfb
4) aes-128-cfb
5) aes-256-cfb8
6) aes-192-cfb8
7) aes-128-cfb8
8) aes-256-ctr
9) aes-192-ctr
10) aes-128-ctr
11) chacha20-ietf
12) chacha20
13) salsa20
14) xchacha20
15) xsalsa20
16) rc4-md5
Which cipher you'd select(Default: aes-256-cfb):12

cipher = chacha20

Please select protocol for ShadowsocksR:
1) origin
2) verify_deflate
3) auth_sha1_v4
4) auth_sha1_v4_compatible
5) auth_aes128_md5
6) auth_aes128_sha1
7) auth_chain_a
8) auth_chain_b
9) auth_chain_c
10) auth_chain_d
11) auth_chain_e
12) auth_chain_f
Which protocol you'd select(Default: origin):5

protocol = auth_aes128_md5

Please select obfs for ShadowsocksR:
1) plain
2) http_simple
3) http_simple_compatible
4) http_post
5) http_post_compatible
6) tls1.2_ticket_auth
7) tls1.2_ticket_auth_compatible
8) tls1.2_ticket_fastauth
9) tls1.2_ticket_fastauth_compatible
Which obfs you'd select(Default: plain):2

obfs = http_simple
```
```
Congratulations, ShadowsocksR server install completed!
Your Server IP        :  47.241.128.25
Your Server Port      :  8099
Your Password         :  tiankx1003
Your Protocol         :  auth_aes128_md5
Your obfs             :  http_simple
Your Encryption Method:  chacha20

Your QR Code: (For ShadowsocksR Windows, Android clients only)
 ssr://NDcuMjQxLjEyOC4yNTo4MDk5OmF1dGhfYWVzMTI4X21kNTpjaGFjaGEyMDpodHRwX3NpbXBsZTpkR2xoYm10NE1UQXdNdy8/b2Jmc3BhcmFtPQ==
Your QR Code has been saved as a PNG file path:
 /root/shadowsocks_r_qr.png

Welcome to visit: https://teddysun.com/486.html
Enjoy it!
```


ssr://NDcuMjQxLjEyOC4yNTo4MDk5OmF1dGhfYWVzMTI4X21kNTpjaGFjaGEyMDpodHRwX3NpbXBsZTpkR2xoYm10NE1UQXdNdy8/b2Jmc3BhcmFtPQ==