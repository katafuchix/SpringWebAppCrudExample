# SpringWebAppCrudExample

- create MySQL DataBase, Table, insert sample data
- create project on Eclipse with Spring Starter Project with maven
- create resources/generatorConfig.xml
- create Entity, Mapper class, XML File (ex.) mvn mybatis-generator:generate
- Add @Data on Entity, @Mapper on Mapper, Define Some Methods on Mapper, XML File
- Add Controller Class / HTML
- Edit App.java
- Edit pom.xml
- Maven install / Build
- copy war file in Tomcat webapps ( Same Java SDK with Eclipse )

http://localhost:8080/user/list

<img width="480" src="https://github.com/katafuchix/SpringWebAppCrudExample/assets/6063541/73889f00-5c87-4626-9d2c-5c78f5c8e1e0">

```
CREATE TABLE `userinfo` (
  `id` BIGINT NOT NULL AUTO_INCREMENT,
  `name` VARCHAR(100) NOT NULL,
  `address` VARCHAR(255) NULL,
  `phone` VARCHAR(50) NULL,
  `update_date` DATETIME NOT NULL,
  `create_date` DATETIME NOT NULL,
  `delete_date` DATETIME NULL,
  PRIMARY KEY (`id`));
```
