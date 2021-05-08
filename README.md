# MySQL安装及配置
<style> g{ font-size:26px; color: #27408B; background: #8B0000; border-radius: 5px; opacity: 85%; } </style>

## 地址

[mysql下载地址](https://dev.mysql.com/downloads/mysql/)

## 正事

- 服务器部署在国💲外，所以翻墙外网下载更快

- 下载好后解压（安装个WinRAR）

- 激活系统先

- 安装好虚拟机💲先安装VM tools

- 然后一键安装环境

- 搜索cmd 然后管理员启动

- 然后cd 进mysql文件中的bin💲目录

- 然后：

    - ①安装服务：mysqld --install
    
    
    - ②初始💲化：　mysqld --initialize --console
    
    
    - ③开启服务：net start mysql
    
    
    - ④关闭服务：net stop mysql
    
    
    - ⑤登录mysql：mysql -u root -p密💲码
    
    
    - ⑥修改密码：alter user 'root'@'localhost' identified by 'root';(by 接着的💲是密码)


<style> g{ font-size:26px; color: #27408B; background: #FA8072; border-radius: 5px; opacity: 85%; } </style>


# SQL指令简单教学

## [进入w3school__sql官网](https://www.w3school.com.cn/sql/index.asp)
## [菜鸟教程](https://www.runoob.com/mysql/mysql-tutorial.html) ------详细

## 创建库
> CREATE DATABASE database_name;

## 创建表

- 先
> use 数据库名字   进入数据库;
- 再
```sql
CREATE TABLE 表名称
(
列名称1 数据类型,
列名称2 数据类型,
列名称3 数据类型,
....
);
```

## 插入
> INSERT INTO 表名称 VALUES (值1, 值2,....);

- 我们也可以指定所要插入数据的列：
> INSERT INTO table_name (列1, 列2,...) VALUES (值1, 值2,....);

# 数据库可视化工具

[DBeaver官网](https://dbeaver.io/download/)

- 里头有mac和win版📢

- 安装好后的连接：
1.点击新建连接，选择mysql
2.填写服务器地址💹以及用户名和密码
3.服务器地址为本地计算机的ip地址，端口为安装mysql时设置的，默认是3306端口
