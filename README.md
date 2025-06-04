# SQL-1
CREATE TABLE
CREATE TABLE users (       
  user_id INT PRIMARY KEY,
  name VARCHAR(50) NOT NULL,
  email VARCHAR(100) UNIQUE,
  age INTEGER CHECK (age >= 18),
  reg_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

INSERT INTO users (user_id, name, email, age)
VALUES (1, 'Soumya sahu',' somyagrkist@gmail.com', 20);

SELECT * FROM users;
