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
`cd /var/www/html`  
2、安装Sqli-labs:  
`git clone https://hub.fastgit.org/mukkul007/sqli-labs-kali2.git`
3、配置文件
`cd sqli-labs/
cd sql-connections/
vi db-creds.inc`

