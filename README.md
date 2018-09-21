# RabbitMQSample4DotNetCore

#### 项目介绍
基于.net core的消息队列实现，封装安装RabbitMQ.client方便使用，实现了竞争者消费模式和发布订阅模式的测试用例，具体使用可参考  
RabbitMQSample4DotNetCore：消息推送  
RabbitMQWorkQueuesSample：竞争者消费模式  
RabbitMQPublishSubscribeSample：发布订阅模式  
  
#### 使用说明

1. 安装RabbitMQ
2. 修改RabbitMQSample4DotNetCore的连接配置
3. 修改RabbitMQWorkQueuesSample和RabbitMQPublishSubscribeSample的连接配置
4. 启动RabbitMQWorkQueuesSample或者RabbitMQPublishSubscribeSample的项目
5. 启动RabbitMQSample4DotNetCore推送消息
6. 查看RabbitMQWorkQueuesSample或者RabbitMQPublishSubscribeSample的项目是否有接收到RabbitMQ推送的消息
