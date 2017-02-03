# proxy.z-project.tech
```
天空没有留下翅膀的痕迹，但我已经飞过
```

# 目标
本项目需要完成的目标

* 统一入口
  * 失败自动重试
  * 自动切换访问代理
* 支持多种代理
  * http
  * https
  * sock5
* 灵活的付费方式
  * 免费
    * 限制访问次数
    * 限制访问流量
  * 付费
    * 按照流量付费
    * 按照请求次数付费
* IP资源
  * 网络
    * 定时爬取
    * 定时清洗
  * 众筹 
    * ADSL用户(拥有外网IP)
    * 机房用户(拥有外网IP)
    * NAT用户(需要隧道协议)

# 优先级
本项目完成的优先级

1. http
2. sock5
3. https(Just a plan)

# 用法
用户只需要设置一次代理即可, 用户手册请访问[proxy.z-project.tech](http://proxy.z-project.tech)
* http
  * 主机名 http.z-project.tech
  * 端口号 8080
* https
  * 主机名 https.z-project.tech
  * 端口号 8443
* sock5
  * 主机名 sock5.z-project.tech
  * 端口号 1080
