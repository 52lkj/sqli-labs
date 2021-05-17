# sqli-labs
learning SQL Injection Techniques
## LAMP环境搭建
### 1、基于Kali手工搭建：  
**启动Apache：**  
`service apache2 start`  
**启动MySQL：**  
`service mysql start`  
**连接MySQL**  
`mysql -u root -p`  
**设置密码**  
`SET PASSWORD FOR 'root'@'localhost' = PASSWORD('新的密码')`  
**切换网站目录**  
`cd /var/www/html`  
### 2、安装Sqli-labs:  
`git clone https://hub.fastgit.org/mukkul007/sqli-labs-kali2.git`  
### 3、配置文件  
`cd sqli-labs/  
cd sql-connections/  
vi db-creds.inc`  
设置数据库密码  
### 4、访问地址  
`http://127.0.0.1/sqli-labs-kali2`  
### 5、点击setup  
## 小结  
1. PHP7.0以上版本注意  
3. 每次开启Sqli-labs前都要先打开apache和mysql  
			`sudo service apache2 start `   
			`sudo service mysql start`
---

