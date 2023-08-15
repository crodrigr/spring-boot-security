# Se crea un proyecto de spring-boot

Este proyecto se va crear con spring-boot **3.1.2** y java **java** y las siguientes dependencias:

### 1. Spring-boot y java

![image](https://github.com/crodrigr/spring-boot-security/assets/31961588/06def656-64c2-434e-a964-1583154f75d9)

<br>
<br>

### 2. Dependencias: Spring Web, JPA, Lombok

La dependencias de JDCB se uso para hacer una prueba de conexión con jdbc, pero se va usar es JPA

![image](https://github.com/crodrigr/spring-boot-security/assets/31961588/766f42c2-1362-444d-a448-2c5212f4c0a0)

<br>
<br>

### 3. Dependencias de security 

![image](https://github.com/crodrigr/spring-boot-security/assets/31961588/4d5ab2a3-250d-40be-9412-e6f512448359)

<br>
<br>

<details><summary>Mostrar código</summary>

<p>   


```xml

<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>3.1.2</version>
		<relativePath/> <!-- lookup parent from repository -->
	</parent>
	<groupId>com.debuggeandoideas</groupId>
	<artifactId>app_security</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<name>app_security</name>
	<description>Demo project for Spring Boot</description>
	<properties>
		<java.version>17</java.version>
	</properties>
	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-jdbc</artifactId>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
		</dependency>

		<dependency>
			<groupId>org.projectlombok</groupId>
			<artifactId>lombok</artifactId>
			<version>1.18.28</version>
			<scope>provided</scope>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>

		<!--OAUTH-2-->
		<dependency>
			<groupId>org.springframework.security</groupId>
			<artifactId>spring-security-oauth2-resource-server</artifactId>
			<version>6.1.2</version>
		</dependency>

		<dependency>
			<groupId>org.springframework.security</groupId>
			<artifactId>spring-security-oauth2-authorization-server</artifactId>
			<version>1.1.1</version>
		</dependency>

		<dependency>
			<groupId>org.postgresql</groupId>
			<artifactId>postgresql</artifactId>
			<version>42.6.0</version>
		</dependency>

	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

</project>


```

</p>
</details>
