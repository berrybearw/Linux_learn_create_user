# Linux_learn_create_user
建立帳號與修改

參考 : 

* https://www.golinuxcloud.com/check-last-password-change-expiration-linux/

密碼
---

換密碼 passwd

root : passwd 帳號

查看密碼最後調整日期

chage -l 帳號

![image](https://user-images.githubusercontent.com/96226780/202847371-d0af54a2-99f4-4537-8947-de48ca4e7835.png)


密碼複雜度
---

[https://www.2daygeek.com/how-to-set-password-complexity-policy-on-linux/](https://www.2daygeek.com/how-to-set-password-complexity-policy-on-linux/)

批次修改用戶 密碼 
---

****chpasswd****

參考 : 

[https://www.cnblogs.com/souhaite/p/10585585.html](https://www.cnblogs.com/souhaite/p/10585585.html)

`echo 帳號:密碼 | chpasswd`
