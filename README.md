
<h1 align="center"> 免责声明 </h1>

只面向海外华人用户且仅供科研学习之用，切勿用于其他用途

           youtube频道：https://www.youtube.com/channel/UClceV39J1Z_9D4_mHkBZrMg

在Value位置填写V2ray的配置信息如下   https://lsland.cn/Technical/OpenShift.html
{
  "log": {
    "loglevel": "warning"
  },
  "inbound": {
    "protocol": "vmess",
    "port": 8080,
    "settings": {
      "clients": [
        {
          "id": "你自己的UUID",
          "alterId": 64,
          "security": "aes-128-gcm"
        }
      ]
    },
    "streamSettings": {
      "network": "ws"
    }
  },
  "inboundDetour": [],
  "outbound": {
    "protocol": "freedom",
   "settings": {}
  }
}
