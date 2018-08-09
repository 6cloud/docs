# 开发规范以及使用技术

## 后端
* 使用python3.5 + django1.11开发
* django-rest-framework构建rest api
* django-rest-framework JWT认证方式、LDAP认证
*

## 前端
* 使用Vue + iView或element ui开发


## 代码遵循PEP8规范
* 分号：不要在行尾加分号, 也不要用分号将两条命令放在同一行.
* 行长度： 每行不超过80个字符。如果遇到较长的导入模块或者注释里的URL不要使用反斜杆
连接行。Python会将 圆括号, 中括号和花括号中的行隐式的连接起来 , 你可以利用这个特点.
如果需要, 你可以在表达式外围增加一对额外的圆括号.例如：
    ```
    def foo(self, username, email, password, phone='', address='shanghai',
                  age=0, height)
    ```
* 行：除非是用于实现行连接, 否则不要在返回语句或条件语句中使用括号. 不过在元组两边
使用括号是可以的.
* 缩进：用4个空格来缩进代码，尽量不要用tab（Pycharm tab设置4个空格可以用）
* 空行：顶级定义之间空两行，方法定义之间空一行。顶级定义比如函数或者类定义空两行，类
定义与定一个方法之间，都应该空一行；函数或方法中某些功能块可以适当空一行。
* shebang：大部分.py文件不必以#!作为文件的开始，但是main文件必须应该以
#!/usr/bin/python开始
* 