# Dude（大佬）

这是一款手工WEB渗透辅助工具，开发这款工具的动机主要是个人在日常进行渗透测试时发现在进行WEB渗透这块主要工具还是由漏扫、浏览器、Burp完成，在空闲的时候把经常使用到的功能集合成一个程序，期望能替代浏览器及Burp的一些常用功能进行快速操作，后续会把这些小工具做成插件供大家在程序里有选择的调用。

# 程序下载 (v1.0.0.2)
完整下载地址：https://github.com/x364e3ab6/Dude/releases/download/v1.0.0.2/Dude_v1.0.0.2.zip

实时更新地址：https://github.com/x364e3ab6/Dude/tree/main

# 插件下载
1. Dude Nmap GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Nmap   
2. Dude Hydra GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Hydra

# 运行环境
.Net Framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上无需额外安装.Net Framework）

# 更新提示 (v1.0.0.2)
1. 新增“漏洞脚本”功能，用于Poc、Exp样本保存及调用；
2. 新增“清理缓存”功能，用于清理WebView2内核的嵌入浏览器及其他产生的临时文件；
3. 新增“随机IP地址”载荷标记，用于爆破时绕过IP限制等需要随机IP地址的地方；
4. 修改“数据重放”，增加了原始请求和验证请求，方便测试Poc、Exp的时候方便修改和比对；
5. 修改了一些小Bug。

# 功能介绍
用户手册实在是懒得写（我错了...请等我的用户手册），粗略介绍一下主要功能和应用范围。

![Dede](https://user-images.githubusercontent.com/73023058/219853233-8ce24bf2-8f2e-4a9a-a086-f123baf1fef4.jpg)

1. 网站浏览、数据监视
  提供常规的网站浏览，主要实现浏览器UserAgent和Cookie的快速修改，配合数据监视可精准定位重要请求以便进行后续的数据包修改，实在不满足还有F12控制台功能，实现更复杂的操作。  
  
2. 数据重放
提供数据改发包功能，在实际应用中什么POC验证、注入、上传、伪造IP、COOKIE都可以在这里实现，并具有插入荷载功能方便操作不可见字符和字符串进行编码加密等，后续更多的功能会增加。
    
3. 数据爆破
提供灵活自定义的爆破功能，在数据重放的基础上实现自动化，主要是通过插入字典标记来实现各类型的爆破，例如账号密码爆破、文件爆破、路径爆破等等，字典标记可结合荷载标记直接让字典实现编码和加密。


