# Robynn
翻墙；

新建：
shadowsocks.json
内容：
 {
    "server":"138.128.221.239",
    "server_port":8388,
    "local_address": "127.0.0.1",
    "local_port":1080,
    "password":"lovejatps",
    "timeout":300,
    "method":"aes-256-cfb",
    "fast_open": false
}

 ssserver -c /etc/shadowsocks.json -d start
