# SpringWebAppCrudExample

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
