# Dude（大佬）

Dude(大佬)是一款半自动WEB渗透测试辅助工具，大佬们可依据自身对漏洞及渗透测试技术的理解使用Dude进行渗透测试工作，手动进行Web渗透测试就目前的来说依然是主流，相比起自动化的扫描器及批量化脚本可以在测试时具有更大的灵活性和准确性来挖掘复现Web应用中的安全风险。目前最好的同类工具当属大家都熟悉的Burp Suite，虽然Dude基本实现了相近的基础功能，但是无论是从性能还是功能都无法与之相比，所以这个工具存在的意义主要还是偏向个人日常使用习惯及对零散的安全工具开发整合。  

程序核心功能为五个部分组成，分别是网站浏览、数据监视、数据重放、数据爆破、工具箱。分别负责几个常见的渗透测试业务场景：网页的浏览调试、浏览调试过程中访问及响应触发的网络数据(HTTP/S数据包)的监视捕获、网络数据的修改重放POC验证的测试、基于网络数据重放的数据暴力破解枚举遍历、外部功能插件的增强、外置程序调用、简单自定义脚本的制作调用、个人网址收藏便捷访问。在工具箱的插件程序中目前已经默认自带使用率非常高的Nmap、Hydra、SQLMap、Awvs的GUI图形化插件（后续缓慢的增加各类使用率较高的功能插件），所有插件在设计时尽可能降低操作步骤及学习成本尽量实现填个地址一键完成，尽量不把时间浪费在调整参数和上网搜索命令示例上，把更多的时间用于思考怎么搞事情。协助渗透大佬提高工作效率更加高效地完成日常KPI及摸鱼，实现一捅天下的霸业。  

目前虽然程序还不成熟，但也不是处于理论阶段，个人已使用他战过CTF、拖过大个库、定向搞过事情、出过安保报告，虽然还有很多不完善的地方但总体目前处于一个可用状态。  

## 程序下载 (v1.0.0.3)

**完整绿色版**（不依赖Edge或Edge WebView2 Runtime）  
下载地址：https://github.com/x364e3ab6/Dude/releases/tag/v1.0.0.3  

**实时更新版**（本机需已安装Edge或Edge WebView2 Runtime）  
下载地址：https://codeload.github.com/x364e3ab6/Dude/zip/refs/heads/main  
Edge WebView2： https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section  

## 更新提示 (v1.0.0.3) 2023.3.25
1. 修改了在安装了Edge或Edge WebView2 Runtime的情况下，可不用携带BrowserRuntime这个超大文件夹；
2. 修改了内置Edge浏览器的一些功能和显示效果；
3. 修改了“数据爆破”功能中同步多线程的问题，极大的提高了爆破速度；
5. 对插件做出一些细节的调整；
4. 修改了一些小Bug。

## 插件下载
Dude Nmap GUI （需本机安装Nmap）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Nmap  

Dude Hydra GUI （无需安装Hydra）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Hydra  

Dude SQLMap GUI （无需安装SQLMap）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/SQLMap  

Dude Awvs GUI （需安装Awvs14使用APIKEY进行通讯）  
下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Awvs  

## 运行环境
.Net Framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上无需额外安装.Net Framework）

## 功能介绍
用户手册实在是懒得写（我错了...请等我的用户手册），粗略介绍一下主要功能和应用范围。

![Dude](https://user-images.githubusercontent.com/73023058/221487446-dcae89e4-fd0a-417c-8771-bbf64d3086e7.jpg)
![Hydra GUI](https://user-images.githubusercontent.com/73023058/221487033-b939846a-43a0-4747-aaa5-ce5973c63546.jpg)
![Nmap GUI](https://user-images.githubusercontent.com/73023058/221487055-d98d4c8d-4e5d-4f45-9177-5c3c05f8f04b.jpg)
![SQLMap GUI](https://user-images.githubusercontent.com/73023058/221487066-dd89f908-a58d-41cd-be9c-60fcd12a63bb.jpg)
![Awvs GUI](https://user-images.githubusercontent.com/73023058/224320478-ddc6fe66-3ce7-4310-8a8a-43400630e9bf.png)

