### nacos

#### nacos 源码搭建

1. 下载源码
2. 安装protobuf 插件，在nacos-consistency模块生成protobuf java 文件
3. 执行mysql 脚本，在distribution 模块下,配置console 模块数据库配置信息
4. 配置jvm 启动参数： -Dnacos.standalone=true -Dnacos.home=C:\\nacos