# sql_lab_primary   by Adam  qq:1073450832      email: adamxxoo@163.com 

本文如有错误，请及时提醒，以免误导他人  qq群：703653509 (后期昂贵付费，暂时免费入群，新群下面有群二维码，认识各种安全大佬，开发大佬，吹牛逼，学知识)

manual sql injection for beginner

手工注入是必须过关的，sql-lab实验室是手工注入必须过关的小游戏吧（印度小哥写的，一共65课，然后我参考lcamry的文件和自己经验写的这个项目使用心得而已）。只有过关了这个基础，才有更多机会绕过各种waf。虽然sql-lab是闯关游戏，但是千万不要以闯关为目的，尽量把每关的每一个注入类型都手工注入一次。最好多做几次。。


本教程对比sqlmap和手工注入学完基本掌握sqlmap语法和手工基础，配合burp一条龙fuzz注入。此处是为了学习原理所以sqlmap用了--proxy= 真是情况不需要代理设置。

本文以黑盒方式注入教程，只有当有一定难度的时候才配合后端源码分析注入过程原理。

phpStudy2016 download url:
链接：https://pan.baidu.com/s/1VdJkXw85ZetFaLw2VvcDhw 
提取码：wdu8 

大神勿扰，本帖子是给刚入门的小新人的。用于手工注入的，欢迎打赏给我动力。虽然我不差你这单打赏,因为写这些分享文章时间我可以赚更多的钱。但是打赏的钱装逼太舒服了

本文如有错误，请及时提醒，以免误导他人 email:    adamxxoo@163.com   

![Image text](https://github.com/Adamloveve/sql_lab_primary/blob/master/IMG/wx.png)
![Image text](https://github.com/Adamloveve/sql_lab_primary/blob/master/IMG/qq.jpg)
![Image text](https://github.com/Adamloveve/sql_lab_primary/blob/master/IMG/alipay.jpg)
