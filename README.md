程序环境为：php8.0 -----------------------必须

程序必须安装：PHP8.0 sg15 扩展包----------必须        如下图安装示例 然后重启php

![image](https://github.com/user-attachments/assets/a3b29a26-6ad6-47be-bb6d-95020088d0e5)

![image](https://github.com/user-attachments/assets/9c4d8d11-0114-49ba-93ca-780250fcb500)


不会影响以前的站点！！！ 不会影响以前的站点！！！ 不会影响以前的站点！！！


url.txt 放需要发布的网站，需要带http协议，比如你需要发布的网站是：1.com

那么url.txt里面就放(https取决于你申请了ssl证书没有，一行一个域名。)：

https://www.1.com


token.json 里面的值必须和网站里面的token一致，防止其他人发布文章到你的网站，示例内容：[{"token":"7FDE2FC008"}]

config.txt 每个网站需要发布多少文章，写1表示发1篇，可以写随机值，比如写：1-5 那么系统会随机选一个数然后进行发布，每个网站取的值不一样。随机性比较大。

article_publisher.php  发布文章则执行这个文件，比如在宝塔上建一个域名或者IP，如果你建的IP是12.12.12.13，那么访问12.12.12.13/article_publisher.php  就可以发布文章了。

宝塔用一个IP建站

![image](https://github.com/user-attachments/assets/d2059ed9-9134-42bf-8ba2-98a4c608b3a6)

下载发布文章的包放进去解压。然后访问你建站的IP/article_publisher.php

![image](https://github.com/user-attachments/assets/0051d2a1-1296-4385-848e-11f4629c348a)

![image](https://github.com/user-attachments/assets/39dd2162-56f0-4b9c-93c5-c89afc33df71)
![image](https://github.com/user-attachments/assets/659acdc6-1b33-4702-9c04-1cfda1a99efa)

系统配置好了后，可以利用宝塔的计划任务。如图所示：
![image](https://github.com/user-attachments/assets/40e0b946-fb09-496a-8e9b-b6c62f49c603)
![image](https://github.com/user-attachments/assets/e27ac3b7-e732-4562-8feb-6fd0a9bbfc38)

有疑问联系TG: @maige50wan
https://t.me/maige50wan
