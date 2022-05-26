# 目的
自动获取Github.com下的域名对应解析到的IP，针对国内用户解决无法正常访问Github的问题

# 思路
参考文章：https://51.ruyo.net/17580.html

# 源码
使用Golang编写，第一次用golang写一些小东西。有不对的地方请大佬们指点！

# 运行
```
#本地需要安装golang环境
go run .\doit.go
```

Windows 可直接运行 github_hosts.exe

Linux 可直接运行 github_hosts

# HOSTS

```bash

####################Github Start####################
140.82.113.25                 alive.github.com
140.82.113.25                 live.github.com
185.199.108.154               github.githubassets.com
140.82.113.21                 central.github.com
185.199.108.133               desktop.githubusercontent.com
185.199.108.153               assets-cdn.github.com
185.199.108.133               camo.githubusercontent.com
185.199.108.133               github.map.fastly.net
199.232.69.194                github.global.ssl.fastly.net
140.82.114.3                  gist.github.com
185.199.108.153               github.io
140.82.112.3                  github.com
192.0.66.2                    github.blog
140.82.113.5                  api.github.com
185.199.108.133               raw.githubusercontent.com
185.199.108.133               user-images.githubusercontent.com
185.199.108.133               favicons.githubusercontent.com
185.199.108.133               avatars5.githubusercontent.com
185.199.108.133               avatars4.githubusercontent.com
185.199.108.133               avatars3.githubusercontent.com
185.199.108.133               avatars2.githubusercontent.com
185.199.108.133               avatars1.githubusercontent.com
185.199.108.133               avatars0.githubusercontent.com
185.199.108.133               avatars.githubusercontent.com
140.82.114.9                  codeload.github.com
52.217.197.185                github-cloud.s3.amazonaws.com
54.231.132.25                 github-com.s3.amazonaws.com
52.217.1.76                   github-production-release-asset-2e65be.s3.amazonaws.com
52.217.203.169                github-production-user-asset-6210df.s3.amazonaws.com
52.216.241.132                github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.108.153               githubstatus.com
64.71.144.211                 github.community
23.100.27.125                 github.dev
140.82.112.22                 collector.github.com
13.107.42.16                  pipelines.actions.githubusercontent.com
185.199.108.133               media.githubusercontent.com
185.199.108.133               cloud.githubusercontent.com
185.199.108.133               objects.githubusercontent.com
# Last Update Time : 2022-05-26 21:01:26 
# Github: https://github.com/malaohu/GitHubHosts 
# Article: https://51.ruyo.net/17580.html 
####################Github End####################

```
