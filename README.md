```

{
  "inbounds": [{
    "port": 1080,
    "protocol": "socks",
    "settings": { "udp": true }
  }],
  "outbounds": [{
    "protocol": "vless",
    "settings": {
      "vnext": [{
        "address": "2.27.22.10",
        "port": 8443,
        "users": [{
          "id": "00178127-ca7e-4fe8-8aab-ee4765c365fb",
          "encryption": "none",
          "flow": "xtls-rprx-vision"
        }]
      }]
    },
    "streamSettings": {
      "network": "tcp",
      "security": "reality",
      "realitySettings": {
        "serverName": "www.cloudflare.com",
        "fingerprint": "chrome",
        "publicKey": "zEd2ONQfkT1UUv0WuUi_3RE1thBz8MXWKADf0xf_6kg",
        "shortId": "6ba85179e30d4fc2"
      }
    }
  }]
}
