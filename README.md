# 基于WireGuard通过ws-scrcpy连接手机（docker容器）

## 创建docker网络

### 创建名为wgnet的网络，IP段为172.20.0.0/24
````
docker network create --subnet 172.20.0.0/24 wgnet
````
