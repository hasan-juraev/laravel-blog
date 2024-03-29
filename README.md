# Haksenguz Informative Platform

<img src='public/logo/haksenguz.jpg' width="100"><br/>

## Laravel, PHP, MySQL, HTML, CSS, Javascript, jQuery, Bootstrap

### Description

[Visit demo of website ](http://ec2-3-35-167-120.ap-northeast-2.compute.amazonaws.com)

Informative Platform that consists of home, blog, portfolio, about,
and contact sections that can be used as a blog/news
website. The project consists of Front pages which is visible to users
and Admin Panel Dashboard for site admins. Laravel’s Breeze a
robust and secure login system is used for Admin Panel. Admin can
(CRUD) Create, Update, Edit, and Delete information which is visible
for users. AWS EC2(Linux CentOS 7) virtual machine host server,
RDS database instance are used to deploy the project to AWS Cloud.

### Features

Login system consists of authentication features, including login,
registration, password reset, email verification, and password
confirmation.


## Tech

- [Laravel 9] - Framework
- [PHP] - Scripting language
- [MySQL] - database
- [HTML]  - Hyper Text Markup Language
- [Twitter Bootstrap] - great UI for modern web apps
- [CSS] - cascading stylesheet
- [Javascript] - Scripting language
- [jQuery] - Javascript library
- [SweetAlert] - Javascript plugin
- [DataTables] - Javascript plugin
- [Apache HTTP Server]


![dashboard](dashboard.png)
 and  **front-end** page. 

![front](front-end.png)

Admin can:
 - insert,
- edit ,
 - update,
- delete,
 data which will be shown on **font-end** page.<br/>
---
**Dashboard** - can be logged in through *login*.<br/>
**Register** - user can register for dashboard.<br/>
**Login** - robust login system with __Laravel Breeze__.<br/>
**Forgot password** - in case of password is lost or forgotten, user can restore password through *email verification*. <br/><br/>
Admin can edit, delete all data,<br>
![dashboard](blog.png)<br/>

add new blogs,
![dashboard](add_blog.png)<br/><br/>

---

## Pre-requisite<br/>
- [Composer](https://getcomposer.org/download/)<br/>
- [Laravel 9](https://laravel.com/docs/9.x/starter-kits)<br/>
- [Intervention Image](https://image.intervention.io/v2)<br/><br/>

---
### Installation<br/>
__1. Composer installation using command line.__<br/>
```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```
2. __[Laravel 9 installation](https://laravel.com/docs/9.x/installation#your-first-laravel-project).__<br/>
You need Apache server to make laravel project. You can download **[XAMPP server](https://www.apachefriends.org/).**<br/>
Open \xampp\htdocs\ folder and make a new folder by giving your project name to it. Then, open command line in this folder.<br/>
After that follow the instructions:<br><br>
**Make a new folder \xampp\htdocs\ inside this folder.**<br/>
![](htdocs.png)<br/><br/>

**Open new folder.**<br/>
![](proj_folder.png)<br/><br/>

**Open command line in this folder. You can simply type ```cmd``` in file path.**<br/>
![](cmd.png)<br/><br/>

**Run the following commands.**<br/>
![](cmd_project_name.png)<br/>

**After that, new folder will be created. This is a folder which contains your new project. Then open this folder and run ```php artisan serve```**<br/>
![](artisan_run.png)<br/><br/>


**Developement Server link will be generated. Copy this link and open it on your browser**<br/>
![](developement_server.png)<br/><br/><br/>

3. __Image Intervention - [follow the instructions given on Image Intervention website](https://image.intervention.io/v2/introduction/installation#integration-in-laravel)__<br><br>

![](imageint.png)<br/><br/><br/>
