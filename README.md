# sql-injection
sql-inject

## mysql页面的函数
mysql_connect(host,username,password,select_database)
打开一个到数据库的连接

mysql_select_db(select_database,connection)
选择数据库

mysql_query()
执行的数据库语句

mysql_fetch_row()
以数组的形式返回查询结果

```php
<?php
header("Content-type:text/html;charset=utf8");

$id = $_GET['id'];

$host = "localhost";
$username = "root";
$password = "";
$sel_database = "security";

$con = 
?>

```
