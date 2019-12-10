# kafka-demo
kafka整合到springboot 实现简单的生产和消费

win10 本地kafka创建

kafka目录下：
1：启动zookeeper
./bin/windows/zookeeper-server-start.bat ./config/zookeeper.properties
2: 启动kafka
./bin/windows/kafka-server-start.bat ./config/server.properties
3：命令行创建topic（话题）
.\bin\windows\kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic testTopic
