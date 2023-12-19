# Dude Suite Web 渗透测试工具

Dude Suite 是一款集成化的Web渗透测试工具集，包含了Web渗透测试活动中使用频率非常高的功能，可以帮助我们高效地完成对Web应用程序的渗透测试和攻击。
测试人员可依据自身对漏洞及渗透测试技术的理解使用DudeSuite进行渗透测试工作，半自动Web渗透测试就目前的来说依然是主流，相比起全自动化的扫描器及批量化脚本可以在测试时具有更大的灵活性和准确性来挖掘复现Web应用中的安全风险。

程序核心功能为六个部分组成，分别是网站浏览、数据监视、结构分析、数据重放、数据爆破、漏洞验证、工具箱。分别负责几个常见的渗透测试业务场景：网页的浏览调试、浏览调试过程中访问及响应触发的网络数据(HTTP/S数据包)的监视捕获、网站结构扫描分析、网络数据的修改重放测试、基于网络数据重放的数据暴力破解枚举遍历及自定义POC漏洞验证、外部功能插件的增强、外置程序调用、自定义Web脚本的制作调用、个人网址收藏便捷访问。提供各类型得GUI图形化插件，所有功能设计时尽可能降低操作步骤及学习成本尽量实现填个地址一键完成，尽量不把时间浪费在调整参数和上网搜索命令示例上，把更多的时间用于思考。  

## 新增下载更新服务器

国内用户在Github使用中如果没有科学上网的话联通性一般，所以新增一台更新服务器作为备用下载升级，满足国内用户的更新下载需求。
更新服务器地址：http://www.dudesuite.cn:8530

## 程序下载

**标准版 v1.2.0.1**  
[点击下载（DudeSuite）](http://www.dudesuite.cn:8530/releases/1.2.0.1/DudeSuite_Standard_Win.zip)
[点击下载（Github）](https://github.com/x364e3ab6/DudeSuite/releases/download/v1.2.0.1/DudeSuite_Standard_Win.zip) 

**迷你版 v1.2.0.1**  
[点击下载（DudeSuite）](http://www.dudesuite.cn:8530/releases/1.2.0.1/DudeSuite_Lite_Win.zip)

## 运行环境
1. Windows10 1709、Windows Server 1709 版本及以上。  
2. 已安装Edge浏览器或Edge WebView2 Runtime，或通过程序更新功能更新绿化的浏览器内核组件。  

## 插件下载  
访问: [http://www.dudesuite.cn:8530 ](http://www.dudesuite.cn:8530/releases/Plugins/)
1. Dude Awvs GUI ：Acunetix Web Vulnerability Scanner（Awvs）漏洞扫描器GUI插件
2. Dude Hydra GUI ：Hydra多协议密码暴力破解工具GUI插件
3. Dude Nmap GUI ：Nmap端口扫描工具GUI插件
4. Dude SQLMap GUI ：SQLMap注入扫描利用工具GUI插件
5. Dude Domain ：子域名爆破及服务探测插件
6. Dude FOFA GUI ：FOFA 网络空间搜索测绘引擎GUI插件
7. Dude ZoomEye GUI : ZoomEye 网络空间搜索测绘引擎GUI插件

## Poc下载
访问: [http://www.dudesuite.cn:8530](http://www.dudesuite.cn:8530/releases/Webpoc/)
1. 涵盖安全系统、安防系统、办公系统、网络系统、文章系统、框架组件等
2. 截至当前版本共201个

## 更新提示 (v1.2.0.1) 2023.10.19
1. 【新增】密文工具，含常见编码解码、散列算法加密解密、JWT令牌的解密及制作；
2. 【新增】小功能如字符串提取等，不进行一一描述；
3. 【改进】数据重放、数据爆破、结构分析、漏洞验证及密文工具可在新窗口打开创建多个实例；
4. 【改进】重写漏洞验证功能，各方面得到增强并对POC进行较全面的验证，新增一批2023HW的POC；
5. 【改进】简化交互及剔除一些看起来还行但很少用到的功能；
6. 【修复】对部分代码BUG、细节和效率进行优化。

## 技术合作团队
HACK之道，专注于红队攻防、实战技巧、CTF比赛、安全开发、安全运维、安全架构等精华技术文章及渗透教程、安全工具的分享。注：微信群过期可加微信号拉入群
![hacklearn](https://github.com/x364e3ab6/DudeSuite/assets/73023058/6f0af6f9-4be1-4585-9350-7855dfafabbc)


## 界面演示

https://github.com/x364e3ab6/DudeSuite/assets/73023058/b0cf9088-a4f3-4c44-9b99-7f14505e9a25



