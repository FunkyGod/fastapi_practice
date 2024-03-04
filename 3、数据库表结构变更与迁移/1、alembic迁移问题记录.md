# 1、迁移表外键为空，无法降级
## create foreign key = None
![](attachments/Pasted%20image%2020240304165343.png)
解决方法
```
任意不重复的字段，两个保持一致就好  
比如 fk_xxx_xxx
```
