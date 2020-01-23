# nodejs-crud-bootstrap
### Database mysql di XAMPP
untuk membuat database baru cukup mengetikkan perintah :
```
CREATE DATABASE crud;
```
membuat table product, beserta kolomnya :
```
CREATE TABLE product(
product_id INT(11) PRIMARY KEY AUTO_INCREMENT,
product_name VARCHAR(200),
product_price INT(11) 
)ENGINE=INNODB;
```
### Pesyaratan
Download dan instal node js dan npm di global 
### Instal Dependencies
membuat package.json di dalam folder :
```
npm init;
```
Dependencies yang dibutuhkan :
* Express js
* mysql
* body Parser
* hbs (Template Engine)
```
npm install --save express mysql body-parser hbs
```
Jalankan Aplikasi "index.js" dengan perintah :
```
node index.js
```
