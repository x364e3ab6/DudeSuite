# Dude Suite Web Security Tools 渗透测试工具集

<p align="center">
  <a href="https://yaklang.io/"><img src="https://github.com/user-attachments/assets/7cb02802-8037-4c3f-a985-730785ecc372" style="width: 400px"/></a> 
 <h2 align="center">Dude Suite Web Security Tools - 渗透测试工具集</h2>
<p align="center">
    
<img src="https://img.shields.io/github/issues-pr/x364e3ab6/DudeSuite/">
<a href="https://github.com/x364e3ab6/DudeSuite/releases"><img src="https://img.shields.io/github/downloads/x364e3ab6/DudeSuite/total">
<a href="https://github.com/x364e3ab6/DudeSuite/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/x364e3ab6/DudeSuite">
<a href="https://github.com/x364e3ab6/DudeSuite/releases/"><img src="https://img.shields.io/github/release/x364e3ab6/DudeSuite">
<a href="https://github.com/x364e3ab6/DudeSuite/issues"><img src="https://img.shields.io/github/issues-raw/x364e3ab6/DudeSuite">
<a href="https://github.com/x364e3ab6/DudeSuite/discussions"><img src="https://img.shields.io/github/stars/x364e3ab6/DudeSuite">
</p>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<p align="center">
    <img src="https://github.com/user-attachments/assets/d6ae07a7-afe8-4f3a-b0d6-4baabd82e5cf"> 
</p>

&emsp;&emsp;DudeSuite（Dude Suite Web Security Tools）是一款轻量化集成化的Web渗透测试工具集程序，程序包含了多种常见的渗透测试场景适用的工具除经典的请求重放及爆破、漏洞验证、端口扫描核心功能外其中的安全工具提供一批常用的功能插件如：常见的编码解码加密破解、网络空间资产搜索、域名爆破、JWT解析爆破、SQLMAP注入等。通过使用程序测试人员可以高效地对Web应用程序进行合规渗透测试及漏洞挖掘验证，复现Web应用中的安全隐患，增强网络的安全性保护重要的数据和系统免受潜在的网络威胁。

### 功能介绍
#### 一、数据重放  
&emsp;&emsp;数据重放功能是DudeSuite中最核心功能，用于对已捕获的HTTP(S)请求进行复现和验证。这一功能对Web渗透测试和漏洞验证至关重要，通过数据重放功能重放网络请求，用户可以选择之前捕获的网络请求重放。这意味着能够以更灵活的方式重现特定的请求，从而验证目标系统对这些请求的响应，或在重放请求之前，对请求的参数、头信息等进行灵活修改，以模拟不同的攻击场景或测试条件。这种灵活性使得测试人员能够进行更为全面的安全评估，探索系统的弱点。  

![数据重放](https://github.com/user-attachments/assets/60bc5d86-d77f-4917-946b-a296cbab6556)


#### 二、数据爆破  
  
&emsp;&emsp;数据爆破功能专门用于针对Web应用中的身份验证和其他输入字段进行高效的暴力破解攻击。请求爆破功能的主要目的是为了解锁受限资源、验证用户名和密码组合的有效性，或者测试其他需要输入的字段，如API密钥、验证码等。通过系统化地尝试大量组合，测试人员能够识别应用程序的脆弱性。用户可以根据具体需求，自定义爆破的参数。例如，指定目录、文件、用户名、密码列表以及相关的请求头、查询参数等，以便精确地针对目标进行攻击。同时，用户可以设置请求的速率，以控制测试过程对目标系统的影响。  

![数据爆破](https://github.com/user-attachments/assets/bbbab198-882f-452e-a4c3-59bd379b4a26)

#### 三、漏洞验证  
  
&emsp;&emsp;漏洞验证功提供自动化的漏洞检测机制，可以针对不同类型的漏洞（如SQL注入、文件上传、命令执行等）进行专门的检测和验证。程序能够自动构建相应的测试用例，减少了手动测试的工作量，提高漏洞验证效率。进行漏洞验证时，程序会捕获和分析服务器的响应，帮助用户识别验证的结果和潜在的信息。漏洞验证的漏洞库为牛马作者为爱发电到处收刮来的当前最流行的漏洞，时效性强复现成功率高，每星期都会对漏洞库进行更新。  

![漏洞验证](https://github.com/user-attachments/assets/edbe8a8b-ad29-4377-92b5-67b717fd8d3e)

#### 四、端口扫描  
  
&emsp;&emsp;端口扫描功能采用高并发全连接扫描方式，扫描效率足够高的同时可以有效规避防火墙对SYN扫描的拦截并快速识别目标主机上开放的端口。服务端口开放情况对于了解网络服务的运行状态，以及判断可能存在的安全漏洞至关重要。在扫描到开放端口后，程序能够进一步识别及主动读取这些端口对应的服务（如HTTP、FTP、SSH等）及其版本信息。这一功能帮助测试人员更加准确的评估服务的安全性。  

![端口扫描](https://github.com/user-attachments/assets/bae370c7-85a4-497f-a339-53a628be8292)

#### 五、安全工具  
  
&emsp;&emsp;安全工具功能集成了多种常用的功能或工具，集成化使得用户可以在一个程序上满足一些常用的需求提升效率，以下是已经完成的功能介绍，后续会根据需求持续增加。  

![安全工具](https://github.com/user-attachments/assets/f82f0dc8-65c4-4fbd-b8cb-5148bec08dbb)
![资产搜索](https://github.com/user-attachments/assets/8f380274-1c1e-4457-a648-516797bb4847)
![SQLMAP](https://github.com/user-attachments/assets/08332c67-457b-4561-9a71-8b340489833c)

SQLMAP GUI：SQLMAP是一个自动化的SQL注入工具，其主要功发现并利用SQL注入漏洞，本功能模块通过GUI的方式快速配置各种场景下所需的SQL注入命令。  

网络地址查询工具：功能模块用于单项或批量查询IP地址的归属地信息，包括经纬度等详细地理位置数据，有效辅助网络攻击朔源及恶意网络地址的排查工作。  

常见编码解码工具：功能模块提供了URL、HEX、Base64、Unicode、ShellCode等常见的编码解码，有效辅助应用系统编解码相关的调试工作。  

域名查询爆破工具：功能模块提供了第三方域名查询接口及多线程域名爆破功能，通过引用域名字典快速寻找存活的子域名发现隐藏的应用系统。  

常见密码加密破解工具：功能模块提供了常见的应用系统用于密码的加密MD5、SM3、SHA等常见散列加密算法，有效辅助日常的密码加密及破解验证工作。  

FOFA 网络空间资产搜索工具：FOFA是一款网络空间测绘的搜索引擎，通过搜索的方式查找互联网资产，本功能模块依据官方API接口实现快速便捷的资产搜索及导出。  

JSON Web Tokens 签发解密工具：功能模块提供了常见的应用系统唯一身份标识 JSON Web Tokens 的签发及解码功能，并提供了在加密的情况下对 Signature 校验签名密钥的破解。  

### 官方网站

https://www.dudesuite.cn 

### 更新细节（v1.0.0.8）

1. 对数据重放交互方式及功能进行优化
2. 修复数据爆破不正确读取字典问题
3. 端口扫描现可以扫描被防火墙拦截的端口
4. 端口扫描现可以在扫描结果双击调用浏览器打开网页应用
5. 端口扫描现可以直接使用域名进行扫描
6. IP地址查询可以正确显示内网地址
7. 漏洞验证的漏洞分类新增最新漏洞显示近30天新增的漏洞
8. 当前版本启用新LOGO

### 程序下载

Windows x64版本下载： [点击下载](https://github.com/x364e3ab6/DudeSuite/releases/download/v1.0.0.8/DudeSuite_v1.0.0.8_win_x64.zip)  

Linux x64版本下载：暂未放出 

MacOS x64版本下载：暂未放出 

MacOS arm版本下载：暂未放出 

### 欢迎关注公众号（星羽安全）
<img src="https://github.com/user-attachments/assets/c9ceb0f4-1f94-44c3-9a4c-545952af0385" alt="星羽安全" style="width:200px;">

### 认证用户微信交流群(3群)
<img src="https://github.com/user-attachments/assets/e0f11b6a-5cad-474f-8d03-31d71d0ce4d6" alt="微信交流群" style="width:200px;">


