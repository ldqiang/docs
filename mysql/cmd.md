1.修改密码复杂度:
   set global validate_password_policy=0;
   show variables like 'validate%';
   alter user user() identified by '123456';
   set global validate_password_length=6;
   
   参考url:https://www.cnblogs.com/ivictor/p/5142809.html
   
2.设置远程访问权限
  GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY '123456' WITH GRANT OPTION;

3.修改密码
  https://blog.csdn.net/sitebus/article/details/96111179
   
