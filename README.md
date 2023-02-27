# Dude（大佬）

这是一款手工WEB渗透辅助工具，主体程序核心功能为网站浏览，HTTP/S流量数据包截获、修改、重发及基于web的各类型爆破，Poc、Exp验证，程序自带脚本三宝Nmap、Hydra、SQLMap的GUI图形化插件高效率完成日常渗透工作，后续更新工作主要是对主体程序BUG修缮及增加各类型的插件。

# 程序下载 (v1.0.0.2)
完整下载地址：https://github.com/x364e3ab6/Dude/releases/tag/v1.0.0.2

实时更新地址：https://github.com/x364e3ab6/Dude/tree/main (更新得文件都不多，直接下载覆盖)

# 插件下载
1. Dude Nmap GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Nmap   
2. Dude Hydra GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/Hydra
3. Dude SQLMap GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/Plus/inside/SQLMap

# 运行环境
.Net Framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上无需额外安装.Net Framework）

# 更新提示 (v1.0.0.2) 2023.2.27
1. 新增“漏洞脚本”功能，用于Poc、Exp样本保存及调用；
2. 新增“清理缓存”功能，用于清理WebView2内核的嵌入浏览器及其他产生的临时文件；
3. 新增“随机IP地址”载荷标记，用于爆破时绕过IP限制等需要随机IP地址的地方；
4. 修改“数据重放”，增加了原始请求和验证请求，方便测试Poc、Exp的时候方便修改和比对；
5. 修改了一些小Bug；
6. 更新了SQLMap插件。

# 功能介绍
用户手册实在是懒得写（我错了...请等我的用户手册），粗略介绍一下主要功能和应用范围。

![Dede](https://user-images.githubusercontent.com/73023058/219853233-8ce24bf2-8f2e-4a9a-a086-f123baf1fef4.jpg)
![Hydra GUI](https://user-images.githubusercontent.com/73023058/221487033-b939846a-43a0-4747-aaa5-ce5973c63546.jpg)
![Nmap GUI](https://user-images.githubusercontent.com/73023058/221487055-d98d4c8d-4e5d-4f45-9177-5c3c05f8f04b.jpg)
![SQLMap GUI](https://user-images.githubusercontent.com/73023058/221487066-dd89f908-a58d-41cd-be9c-60fcd12a63bb.jpg)
