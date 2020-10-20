rabbitmq
#########

RabbitMQ is the most widely deployed open source message broker.

安装
*****

完整安装文档`点击`_
.. 点击:https://www.rabbitmq.com/download.html

docker
*******

安装::

    docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
