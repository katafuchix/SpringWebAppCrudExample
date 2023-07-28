# SpringWebAppCrudExample

http://localhost:8080/user/list

<img width="480" src="https://github.com/katafuchix/SpringWebAppCrudExample/assets/6063541/d8ae7774-3b2a-4577-bc43-f70edd818538">

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
