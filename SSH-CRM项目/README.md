# SSH_CRM
# 简单的spring+struts2+Hibernate整合项目
是一个crm人员关系管理系统。

管理员登陆系统可以对录入系统内的人员进行增删查改。

是一个练习ssh框架整合的入门项目，同时可以熟悉hibernate进行增删查改的操作。

技术上的提升：
- 在web层和dao层都提取了公共代码封装到BaseAction和BaseDao中，提高了代码的复用，同时按照OO设计原则，针对接口编程，而不是针对实现编程。
- 使用拦截器的方法对系统权限进行初步控制（后续可以采用Shiro框架进行更新)
- 对用户的密码采用MD5加密方法进行加密（可以采取多次MD5加密方式，和其他加密方式）

## 项目页面如下
---
![image](images/login.png)

![image](images/index.png)
