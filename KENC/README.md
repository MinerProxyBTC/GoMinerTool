<div align="center">

# 本地加密隧道文档说明

</div>

<p id="kenc"></p>

### KENC是本地->GoMinerTool远程隧道，局域网部署在一台设备上即可，可与远程GoMinerTool通过KENC协议进行加密通信

<a href="https://github.com/MinerProxyBTC/GoMinerTool/raw/main/KENC/windows.zip">点击下载WINDOWS客户端</a>

<a href="https://github.com/MinerProxyBTC/GoMinerTool/raw/main/KENC/kenc_linux_amd64">点击下载LINUX客户端</a>

<a href="https://github.com/MinerProxyBTC/GoMinerTool/raw/main/KENC/kenc_linux_arm64">点击下载ARM平台客户端</a>

#### Linux系统手动安装：
先cd到对应目录，然后运行nohup ./kenc_v_linux &
隧道自带守护;
#### Linux本地加密国内一键安装脚本：
```
bash <(curl -s -L https://cdn.jsdelivr.net/gh/MinerProxyBTC/GoMinerTool@main/jm.sh)
```

### 使用环境
```
GoMinerTool版本>=2.6.0
```

## 使用说明

### 1.远程GoMinerTool先配置一个KENC协议的端口

<img src="./../image/t14.png" alt="Logo" width="300">

### 2.在Go的设置页面找到KENC配置推送, 如下图
<img src="./../image/kenc.png" alt="Logo">

### 3. KENC客户端首次打开, 或点击右上角设置, 即可更改配置推送地址, 配置设置完毕后重启KENC客户端即可拉取最新配置
