# config-server-git

使用spring-cloud-config 功能的server端。
使用[https://github.com/zhunhuang/config-remo-demo](https://github.com/zhunhuang/config-remo-demo)作为配置仓库

## 启动

spring boot 工程，入口类：src/main/java/com/example/configservergit/ConfigServerGitApplication启动。

## 本地调试
启动后，本地访问[http://localhost:1200/config-client/dev/master](http://localhost:1200/config-client/dev/master)
即可获取到[https://github.com/zhunhuang/config-remo-demo/blob/master/config-client-dev.yml](https://github.com/zhunhuang/config-remo-demo/blob/master/config-client-dev.yml)文件的内容。

参考教程：
https://www.jianshu.com/p/55e92b06a7fd
