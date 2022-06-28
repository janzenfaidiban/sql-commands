# SQL COMMANDS

## CREATE DATABASE

	CREATE DATABASE databasename

## DROP DATABASE

	DROP DATABASE databasename

## CREATE TABLE

	CREATE TABLE users (
	    id INT(11) NOT NULL AUTO_INCREMENT,
	    first_name VARCHAR(50) NOT NULL,
	    last_name VARCHAR(50) NULL,
	    email VARCHAR(50) NULL,
	    PRIMARY KEY (id)
	)

## DROP TABLE

	DROP TABLE tablename

## INSERT DATA

	INSERT INTO `users`(`id`, `first_name`, `last_name`, `email`) VALUES ('','Janzen', 'Faidiban', 'janzenfaidiban@gmail.com')

## UPDATE DATA

	UPDATE `users` SET `first_name`='Michael', `last_name`='Janzen', `email`='michaeljanzen@gmail.com' WHERE `id`=1

## DELETE DATA

	DELETE FROM `users` WHERE `id`=1

