# 命令行设置代理

## 设置配置 
vi .bash_profile
```
alias proxy='export all_proxy=socks5://127.0.0.1:1080'
alias unproxy='unset all_proxy'
```
source .bash_profile

## 查看当前ip信息
curl ipinfo.io

## 开启代理
proxy

## 关闭代理
unproxy