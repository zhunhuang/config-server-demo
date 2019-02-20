# config-server-git

使用spring-cloud-config 功能的server端。
使用[https://github.com/zhunhuang/config-remo-demo](https://github.com/zhunhuang/config-remo-demo)作为配置仓库

## 启动

IDE运行，ConfigServerGitApplication的main方法即可。

## 本地调试
启动后，本地访问[http://localhost:1200/config-client/dev/master](http://localhost:1200/config-client/dev/master)
即可获取到[https://github.com/zhunhuang/config-remo-demo/blob/master/config-client-dev.yml](https://github.com/zhunhuang/config-remo-demo/blob/master/config-client-dev.yml)文件的内容。
