# spring-boot-stady-common-utils


1、项目说明

spring-boot-stady框架基础工具包封装（包含以下功能）

	1、redis

	2、kafka

	3、mongo

	4、poi

	5、图片处理

	6、加密算法

	7、fastdfs

	8、大文件上传下载的封装

	9、rabbitmq

	10、activemq

	11、excel处理

	。。。。。



2、包结构说明

	com.yang.springboot.stady：spring-boot-stady架构跟目录

		|----common：bingo架构工具包基础目录

			|----mybatis：mybatis二级缓存基础配置

				|----MybatisCacheSetRedisTemplate：设置redisTemplate

				|----MybatisRedisCache：重写mybatis缓存实现类

			|----redis：redis基础配置

				|----RedisConfig：redis基础配置

				|----RedisKeyGenerator：redis key值生成器

				|----RedisService：redis基础服务

			|----ArrayUtils：数组工具类






