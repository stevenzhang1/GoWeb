# GoWeb
关于go项目代码

#使用go mod管理第三方包
## export GO111MODULE=on   export GOPROXY="https://athens.azurefd.net"
```
1).go mod init project_name
2).编写代码
3).go mod vendor 下载第三方包到vendor以及整理本地包
4).go build -mod=vendor
5).docker run -it  -p 127.0.0.1:8083:8083 f2e0bfd99850 

```


