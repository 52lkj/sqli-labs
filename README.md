# sqli-labs
learning SQL Injection Techniques
## LAMP环境搭建
1、基于Kali手工搭建：  
启动Apache：  
`service apache2 start`  
启动MySQL：  
`service mysql start`  
链接MySQL  
`mysql -u root -p`  
设置密码  
`SET PASSWORD FOR 'root'@'localhost' = PASSWORD('新的密码')`  
切换网站目录  
`cd /var/www`  
创建index  
`touch index.php`  
` vim index.php`  
`<?php phpinfo();?>`
2、安装Sqli-labs:  
`git clone https://github.com/himadriganguly/sqlilabs.git`

