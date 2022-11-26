# ncku_web

MYSQL:
```
create database ncku_w;
show databases;
use ncku_w;
CREATE TABLE `ncku_w`(
		`index` INT AUTO_INCREMENT,
        `username` VARCHAR(20) NOT NULL,
        `id` VARCHAR(100) NOT NULL,
        `hpname` VARCHAR(20) NOT NULL,
        `time_` VARCHAR(1000) NOT NULL,
		PRIMARY KEY(`index`)
        );
select * from `ncku_w`;
Drop TABLE `ncku_w`;
delete  from  `ncku_w` where id>1;```
