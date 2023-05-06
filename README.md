# Dude（大佬）

Dude(大佬)是一款半自动WEB渗透测试辅助工具，大佬们可依据自身对漏洞及渗透测试技术的理解使用Dude进行渗透测试工作，手动进行Web渗透测试就目前的来说依然是主流，相比起自动化的扫描器及批量化脚本可以在测试时具有更大的灵活性和准确性来挖掘复现Web应用中的安全风险。目前最好的同类工具当属大家都熟悉的Burp Suite，虽然Dude基本实现了相近的基础功能，但是无论是从性能还是功能都无法与之相比，所以这个工具存在的意义主要还是偏向个人日常使用习惯及对零散的安全工具开发整合。  

程序核心功能为五个部分组成，分别是网站浏览、数据监视、结构分析、数据重放、数据爆破、工具箱。分别负责几个常见的渗透测试业务场景：网页的浏览调试、浏览调试过程中访问及响应触发的网络数据(HTTP/S数据包)的监视捕获、网站结构扫描分析、网络数据的修改重放POC验证的测试、基于网络数据重放的数据暴力破解枚举遍历、外部功能插件的增强、外置程序调用、简单自定义脚本的制作调用、个人网址收藏便捷访问。在工具箱的插件程序中目前已经默认自带使用率非常高的Nmap、Hydra、SQLMap、Awvs的GUI图形化插件（后续缓慢的增加各类使用率较高的功能插件），所有插件在设计时尽可能降低操作步骤及学习成本尽量实现填个地址一键完成，尽量不把时间浪费在调整参数和上网搜索命令示例上，把更多的时间用于思考怎么搞事情。协助渗透大佬提高工作效率更加高效地完成日常KPI及摸鱼，实现一捅天下的霸业。  

目前虽然程序还不成熟，但也不是处于理论阶段，个人已使用他打过CTF、拖过库、定向搞过事情、出过安保报告，虽然还有很多不完善的地方但总体目前处于一个可用状态。  

## 交流反馈可加QQ群：6439987  

## 程序下载 (v1.0.0.4)

**实时更新版**（本机需已安装Edge或Edge WebView2 Runtime）  
下载地址：https://codeload.github.com/x364e3ab6/Dude/zip/refs/heads/main  
Edge WebView2 Runtime： https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section  

**完整绿色版**（不依赖Edge或Edge WebView2 Runtime）  
下载地址：https://github.com/x364e3ab6/Dude/releases/tag/v1.0.0.4  

## 版本更新预告
预计下个版本会进行以下调整，调整幅度比较大：  
1. 新增工具箱插件程序的导入加载卸载，将插件打包并加载时提供可能需要的依赖安装，主程序默认不再自带所有插件，独立开辟一个插件专区供下载；  
2. 新增漏洞扫描功能及webPoc、psPoc编辑器，大概率引入goby的Poc及powershell的Poc，制定webPoc及psPoc编制规范；  
3. 预计新增漏洞利用功能及webExp、psExp编辑器，Poc和Exp本质其实没什么区别，但是在配置操作执行细节上可能得再考虑，所以可能会在漏洞扫描完善后再新增此功能；  
4. 原来的漏洞利用功能修改为请求脚本功能，作为请求测试验证的附带基础功能；  
5. 优化原先已有插件，预计新增Domain扫描插件、空间测绘插件（zoomeye或fofa）；  
6. 鉴于改动的东西较多，下个版本号暂定为：v1.1.0.1  

## 不完全版本更新 (v1.0.0.5) 2023.5.6
修复一个数据监视功能使用异步委托引起的“灾难性故障”；  
测试显示使用Edge浏览器最新版本（112.0.1722.64）的Chrome内核在浏览请求特别多的网站会导致一个 HRESULT:0x8000FFFF 的报错，但使用老版本内核（109.0.1518.70）则不会出现；  
本次升级并不是必须的只是觉得这个BUG挺影响心情的，要升级直接下载独立的Dude.exe覆盖即可。  

## 更新提示 (v1.0.0.4) 2023.4.30
1. 新增结构分析功能，可快速分析网站结构，并可对指定链接执行JavaScript脚本获取常规源码分析无法取得的链接，如各种WebAPI和基于vue前端开发的网站；
2. 新增内置浏览器注入并执行JavaScript脚本的功能；
3. 新增了工具箱的显示隐藏，默认隐藏；
4. 修改了内置浏览器及功能插件TabControl的重选中逻辑和关闭方式；
5. 修改了数据监视功能由始终开启为自定义开启；
6. 修改了一些小Bug，对部分代码写法和效率进行优化；
7. 内置Edge浏览器Chrome内核升级至最新版本112.0.1722.64。

## 插件独立下载
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
用户手册写起来真的很讨厌，我有时间的时候已经尽量在写了，先图片粗略介绍一下主要功能。
![0](https://user-images.githubusercontent.com/73023058/235344102-bb5d2675-dbc6-4e84-80f9-9d0eef11b8c5.png)
![1](https://user-images.githubusercontent.com/73023058/235344094-86e9076f-1ef4-410b-a306-44ed27904052.png)
![2](https://user-images.githubusercontent.com/73023058/235344097-b06e14a5-08c3-48c0-a609-27f82e994e0e.png)
![3](https://user-images.githubusercontent.com/73023058/235344098-94906d58-fed7-466c-9a9e-966aa6c3c90c.png)
![4](https://user-images.githubusercontent.com/73023058/235344099-e5979d45-8f1f-4e14-83c0-d404c23954f4.png)
![5](https://user-images.githubusercontent.com/73023058/235344100-13a175c1-fc0d-4090-827e-6bf971bfe8c0.png)
![Hydra GUI](https://user-images.githubusercontent.com/73023058/221487033-b939846a-43a0-4747-aaa5-ce5973c63546.jpg)
![Nmap GUI](https://user-images.githubusercontent.com/73023058/221487055-d98d4c8d-4e5d-4f45-9177-5c3c05f8f04b.jpg)
![SQLMap GUI](https://user-images.githubusercontent.com/73023058/221487066-dd89f908-a58d-41cd-be9c-60fcd12a63bb.jpg)
![Awvs GUI](https://user-images.githubusercontent.com/73023058/224320478-ddc6fe66-3ce7-4310-8a8a-43400630e9bf.png)



