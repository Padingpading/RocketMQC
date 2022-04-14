#启动
##nameserver
NameServerInstanceTest.main
##broker
BrokerControllerTest.main
##consumer
Producer.main 
#Consumer



##启动nameserver
org.apache.rocketmq.namesrv.NamesrvStartup
添加Enviroment Variable加载配置。
ROCKETMQ_HOME=E:\sorucecode\RocketMQC\z-conf

##启动broker
org.apache.rocketmq.broker.BrokerStartup
添加Program arguements 指向配置文件
-c E:\sorucecode\RocketMQC\z-conf\conf\broker.conf 
添加Enviroment Variable 指向配置文件地址
ROCKETMQ_HOME=E:\sorucecode\RocketMQC\z-conf



