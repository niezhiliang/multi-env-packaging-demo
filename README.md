# 多环境只打包某一个环境的配置到包中

打包命令指定两个环境

mvn clean install -P env-sjt,test -DskipTests=true


pom文件中不能继承parent标签
