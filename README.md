
<p align="center">
  <h1 align="center">DudeSuite Web Security Tools - 单兵作战渗透测试工具</h1>
</p>

<p align="center">
<a href="https://www.dudesuite.cn/" target='_blank'><img src="https://img.shields.io/badge/%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99-%E7%82%B9%E5%87%BB%E6%89%93%E5%BC%80style=square"></a>
<a href="https://github.com/x364e3ab6/DudeSuite/releases/"><img src="https://img.shields.io/github/release/x364e3ab6/DudeSuite?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC&style=square"></a>
<a href="https://github.com/x364e3ab6/DudeSuite/issues"><img src="https://img.shields.io/github/issues-raw/x364e3ab6/DudeSuite?label=%E9%97%AE%E9%A2%98%E5%8F%8D%E9%A6%88&style=square"></a>
<a href="https://github.com/x364e3ab6/DudeSuite/discussions"><img src="https://img.shields.io/github/stars/x364e3ab6/DudeSuite?label=%E7%82%B9%E8%B5%9E%E6%98%9F%E6%98%9F&style=square"></a>
</p>

<p align="center">
    <img src="https://github.com/user-attachments/assets/e8fa15b8-9964-4c24-b6dd-e92b6bc59a9e"> 
</p>

<p style="line-height: 2.5;">
&emsp;&emsp;DudeSuite（Dude Suite Web Security Tools）是一款轻量化集成化的Web渗透测试工具集程序，程序包含了多种常见的渗透测试场景适用的功能：重放及爆破、漏洞验证、端口扫描、流量劫持、远程管理等，其中的安全工具提供一批常用的功能插件如：常见的编码解码加密破解、网络空间资产搜索、域名爆破、JWT解析爆破、SQLMAP注入等。通过使用程序测试人员可以高效地对Web应用程序进行合规渗透测试及漏洞挖掘验证，复现Web应用中的安全隐患，增强网络的安全性保护重要的数据和系统免受潜在的网络威胁。
</p>


#### 更新日志（v1.2.1.4）

1. 修复多个已知BUG
2. UI调整及多项优化改进

#### 版本兼容

| Windows x64 | macOS x64 | macOS Arm64 |
| :----:| :----: | :----: |
| Win7~11 | macOS 15+ | macOS 15+ |

#### 安装说明

1. Windows版本：支持win7及更高版本操作系统，解压即可使用，无组件依赖。
2. macOS版本：加载DMG镜像后直接将DudeSuite.app拖拽至应用程序目录（Applications、应用程序）即可
3. macOS版本如出现“DudeSuite.app已损坏,无法打开”是因为程序没有苹果签名，解决方法控制台：
   
   `允许安装第三方来源APP：sudo spctl --master-disable`
   
   `删除程序隔离属性：sudo xattr -r -d com.apple.quarantine /Applications/DudeSuite.app`

#### 公众号
<img src="https://github.com/user-attachments/assets/1fa2ddec-b536-4649-bbaa-374f8dbee43e" alt="星羽安全" style="height:120px;">
