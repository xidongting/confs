# confs

## mihomo
> mihomo自用配置备份
### 规则集
1. direct.list
    - classical格式
    - 收集不需要走远程的域名
    - 以此为基础配置fake-ip-filter，尽可能让大陆ip流量绕过核心
2. proxy.list
    - classical格式
    - 收集需要走远程代理的域名或ip
3. ai.list
    - classical格式
    - 单独维护生成式AI产品域名，让这些域名统一走美国代理