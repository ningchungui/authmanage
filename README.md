auth manage
===============

这是一个统一管理系统权限，设计的目标是给开发者一个完整地权限管理系统，以便你能更专注自己系统业务的开发

## 特点

1. 统一配置界面
1. 简洁的客户端SDK包
1. 支持不同平台，不同语言
1. 易扩展
1. 粒度随意掌控，可大可小
1. 支持spring

## 安装与运行

1. 运行之前请先安装maven和git
2. 将代码clone到本地后，需要先修改./auth-web/src/man/filters/dev.properties,配置你自己的数据库连接
2. 执行sh run.sh，成功启动后访问 [http://localhost:8888](http://localhost:8888)，如果看到登陆页面，说明程序启动成功

## 数据库生成




