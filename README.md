# RabbitMq Server
## rabbitMq install
- $ sudo apt-get install rabbitmq-server
- $ sudo rabbitmq-plugins enable rabbitmq_management
- $ sudo service rabbitmq-server restart

## add admin
- $ sudo rabbitmqctl add_user {id} {password}
- $ sudo rabbitmqctl set_user_tags rabbitmq administrator

## management site connetion
- http://localhost:1562/

## add service account
- management site - Admin - Users - Add auser
(Tags: None)

## add Virtual Host
- management site - Admin - Virtual Hosts - Add virtual host

## Virtual Host Permissions
- management site - Admin - Virtual Hosts
- target host select
- Set permissions 

# install
- $ sudo pip install pika
