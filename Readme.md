# Spring boot Azure Cache for Redis Example

## Maven dependencies for Redis

```xml
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-redis</artifactId>
		</dependency>
```

## Spring properties

```
spring.redis.host=<rediscaheName>.redis.cache.windows.net
spring.redis.port=6380
spring.redis.password=<redis access key>
spring.redis.ssl=true

```