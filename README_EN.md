# sing-box-yes  
sing-box manager

sing-box is a universal proxy platform which supports multiple protocols.
Please check [official site](https://sing-box.sagernet.org/) for more details.
# Usage
```
bash <(curl -Ls https://raw.githubusercontent.com/zswdcx/sing-box-yes/master/install-pre.sh)
```    
To install a specific version, use flag `install`:
```
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/sing-box-yes/master/install-pre.sh) install 1.9.7
```
# Quick Start
Type `sing-box` to enter control menu, u.i.:
```
sing-box-v0.0.1 管理脚本
  0. 退出脚本
————————————————
  1. 安装 sing-box 服务
  2. 更新 sing-box 服务
  3. 卸载 sing-box 服务
  4. 启动 sing-box 服务
  5. 停止 sing-box 服务
  6. 重启 sing-box 服务
  7. 查看 sing-box 状态
  8. 查看 sing-box 日志
  9. 检查 sing-box 配置
————————————————
  A. 设置 sing-box 开机自启
  B. 取消 sing-box 开机自启
————————————————
  C. 一键开启 bbr 
  D. 一键申请SSL证书
 
[INF] 版本信息:sing-box 1.0.4.d2add33 (go1.19.1, linux/amd64, CGO disabled) 
[INF] sing-box状态: 已运行
[INF] sing-box是否开机自启: 是
[INF] ##################### 
[INF] 进程ID:2615900 
[INF] 运行时长：Thu 2022-09-15 16:29:14 CST; 1s ago  
[INF] 内存占用:11488 kB 
[INF] ##################### 
[INF] 配置文件路径:/usr/local/etc/sing-box/config.json 
[INF] 可执行文件路径:/usr/local/bin/sing-box 
```   
# examples  
- client_config.json will be used as client config,inbound:`tun`,outbound:`shadowsocks`  
- server_config.json will be used as server config,inbound:`shadowcoks`,outbound:`direct`  


