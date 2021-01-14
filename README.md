# x-gorgon/xlog
抖音xg04算法和设备号风控研究  

Douyin/Tiktok algorithms including x-gorgon, xlog, register and activate devices

本项目主要是针对抖音和Tiktok爬虫业务的研究。要实现一个大并发且稳定的爬虫， 至少具备以下条件:
* IP
* 设备号注册激活
* Xg03/04 算法
* 合理的软件设计

2020年8月的抖音风控调整， 对很多伙伴的业务造成巨大的影响。其实要修复此问题，只需要在几个方面做改进
1. IP 国内的IP池严重复用。
2. 设备号 这是抖音风控目前针对的主要方向。绕过它，是核心关键。 单纯的发log，不足以解决。
3. Xg算法 市面上的xg04算法，有一个漏洞会造成成功率缺陷。
4. 软件设计 爬取逻辑的调整比较好处理。 事实上抖音各个接口具有不同的风控，需单独调整。

欢迎大家与我交流。

联系方式/Contact me  

Telegram: https://t.me/marketabc
