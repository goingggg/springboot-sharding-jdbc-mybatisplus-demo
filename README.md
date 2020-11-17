# mybatis-plus+sharding-jdbc+springboot
mybatis-plus+sharding-jdbc+springboot2.x整合mysql读写分离
#sql
CREATE TABLE `user` (
  `id` VARCHAR(255) NOT NULL,
  `name` VARCHAR(255) DEFAULT NULL,
  `mobile` VARCHAR(64) DEFAULT NULL,
  PRIMARY KEY (`id`)
) 
#Docker Compose搭建MySQL主从复制集群
https://blog.csdn.net/baidu_22254181/article/details/82701676

