1.修改密码复杂度:
   set global validate_password_policy=0;
   show variables like 'validate%';
   alter user user() identified by '123456';
   set global validate_password_length=6;
   
   参考url:https://www.cnblogs.com/ivictor/p/5142809.html
   
