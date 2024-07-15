# LAN-toolkit
## 软件
- [**ZeroTier**](https://www.zerotier.com/)
- [RustDesk](https://github.com/rustdesk/rustdesk)
- [RustDesk Server](https://github.com/rustdesk/rustdesk-server)
- [简传](https://easysend.channer.cn/)
- [TeamSpeak](https://www.teamspeak.com/zh-CN/)
## 功能概览

| 软件              | 功能                  |
| --------------- | ------------------- |
| **ZeroTier**    | 提供虚拟局域网             |
| RustDesk        | 远程控制 支持自建服务器和官方服务器  |
| RustDesk Server | 自建服务器               |
| 简传              | 局域网文件传输+文字传输        |
| TeamSpeak       | 语音+聊天 支持自建服务器和官方服务器 |

## 配置
### **ZeroTier**
- 下载并安装[**ZeroTier**](https://www.zerotier.com/download/)
- 安装后自动打开，在任务栏托盘右键ZeroTier即可配置
- Join Network加入局域网 我们的局域网ID在群里
在cmd中输入ipconfig可以看到Zerotier分配的虚拟局域网IP



### RustDesk
- 下载并安装[RustDesk](https://github.com/rustdesk/rustdesk/releases/tag/1.2.6).Assets下会有很多供给不同操作系统和系统架构的包,我们都是x86架构的Windows 64位系统,下载[rustdesk-1.2.6-x86_64.exe](https://github.com/rustdesk/rustdesk/releases/download/1.2.6/rustdesk-1.2.6-x86_64.exe)或[rustdesk-1.2.6-x86_64.msi](https://github.com/rustdesk/rustdesk/releases/download/1.2.6/rustdesk-1.2.6-x86_64.msi)即可
- 在设置-网络中设置中继服务器
- 在ID服务器输入我部署的服务器IP:10.243.236.173
- 在Key输入服务器授权密钥:B0eCXMC8hUIviCULXH9STBoqGd+hlpdiJXbmnU4fJr0=
- 应用即可
### 简传
> 简传是一个使用浏览器网址访问的传输应用,且局域网中仅需配置一个简传服务,我会一直开着简传服务,在浏览器输入 http://10.243.236.173:7072 可访问。有兴趣可以自己装个玩玩

### TeamSpeak
- 下载并安装[TeamSpeak TS5 Client](https://www.teamspeak.com/zh-CN/downloads/#ts5client)
- 注册账号并验证邮箱
- 打开后点击左侧栏上方的齿轮图标进入设置
- 点击Appearance,找到Language可切换成中文
- 重启后在右边加入一个TeamSpeak服务器下输入10.243.236.173进入服务器
