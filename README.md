# 一键部署 v2ray 到 heroku[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

#客户端配置 client_config.json, 

1.部署时配置 v2ray core 的版本、Vmess协议的UUID（"alterId"默认为64）和连接缓存。

2.服务端部署后，应 open app ，显示 Bad Request，表示部署成功。

3.更新 v2ray 版本，修改 app settings-->Config Vars-->VER，程序自动重启，通过view Logs确认。

4.客户端配置 client_config.json, 建议使用 cn_sniproxy+websocket+tls 传输协议。

nslookup  us-east-1-a.route.herokuapp.com 8.8.8.8

# 参考 

https://github.com/onplus/v2hero/

https://toutyrater.github.io/

https://www.v2ray.com/

#PC端

https://github.com/v2ray/v2ray-core/releases

https://github.com/2dust/v2rayN/releases

https://github.com/Cenmrev/V2RayW/releases

#Android端

https://github.com/2dust/v2rayNG/releases

https://github.com/V2Ray-Android/Actinium/releases

#ios端

https://www.v2ray.com/itunes/us/pepi/id1283082051/

https://www.v2ray.com/itunes/us/kitsunebi/id1275446921/

https://www.v2ray.com/itunes/us/shadowrocket/id932747118/
