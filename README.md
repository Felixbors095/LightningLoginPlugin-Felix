# LightningLoginPlugin-Felix


my sql code:
CREATE TABLE `lightninglogin`.`Untitled`  (
  `email` text NULL,
  `uid` text NULL,
  `code` int(11) NULL,
  `password` text NULL,
  `flag` int(1) NULL
);
这款插件在注册时必须绑定邮箱。绑定的时候回向注册者发送随机6位数的验证码
![image](https://github.com/Felixbors095/LightningLoginPlugin-Felix/assets/88223220/d823f6c1-0de9-4c6c-a5c9-7bcfc478f10f)


绑定后会发送验证码到玩家邮箱里
![image](https://github.com/Felixbors095/LightningLoginPlugin-Felix/assets/88223220/063e0816-802f-4889-a512-06ab50610c6d)


在config里配置
具体如何开启qq SMTP的服务自行搜索
![image](https://github.com/Felixbors095/LightningLoginPlugin-Felix/assets/88223220/0995bbbf-ef70-4040-b5ab-99c3050bd736)


输入玩这些后会有提示
![image](https://github.com/Felixbors095/LightningLoginPlugin-Felix/assets/88223220/da264412-f98a-4375-9ca3-6933b3bfa011)


这样就可以登录了！
同时插件命令支持中文

##只支持数据库！！！！！
##在Config里配置


在数据库里执行命令
CREATE TABLE `lightninglogin`.`Untitled`  (
  `email` text NULL,
  `uid` text NULL,
  `code` int(11) NULL,
  `password` text NULL,
  `flag` int(1) NULL
);

<a href="https://github.com/Felixbors095/LightningLoginPlugin-Felix/blob/main/E-README.md">English</a>
