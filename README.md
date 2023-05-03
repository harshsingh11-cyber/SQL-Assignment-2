# SQL-Assignment-2


CREATE DATABASE todo_list;

USE todo_list;

CREATE TABLE tasks (
  task_id INT PRIMERY KEY,
  task_name VARCHAR(255) ,
  description VARCHAR(255),
  is_completed TINYINT(1) DEFAULT 0,
);
