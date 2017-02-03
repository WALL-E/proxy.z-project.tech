# DYNAMIC SOCK5 PROXY
使用nginx http模块实现

## 优点
使用ngx.balancer动态修改后端服务器地址，不需要重启Nginx进程

## 配置文件
* proxy.conf 正向代理配置文件
* nginx.conf 反向代理配置文件
  * 四层代理
  * 七层代理(默认)
