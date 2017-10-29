# readme-skill
readme的使用技巧
### 标题使用方法
    使用#加一个空格
    标题有等级六个等级，显示的文本大小依次减小。
    不同等级之间是以井号#的个数来区别。一级标题有一个#，二级标题有两个#，以此类推至六级标题。
### 单行文本
    在文本的前面加上两个Tab即可得到这个效果
### 多行文本
    这是第一行，前面加了两个Tab
    这是第二行，前面加了两个Tab
    这是第三行，前面加了两个Tab
    多行文本行单行文本的原来都是一样，在文本的前面加两个Tab
### 内容突出显示
    `内容突出显示`
    
使用方法：这是`突出`部分，用的是''包含内容,但注意是这里的``并不是单引号，而是Tab键上面的`
### 文本超链接
[这是超链接](http://baidu.com)

使用方法：这里的格式为\[]()，[]里面填写显示超链接的文字，()里面填写超链接地址
### 插入圆点符
* 测试一
* 测试二

使用方法：这里用*符号然后加一个空格可以实现
### 多层分级
* 测试一分级
  * 测试一分级的一分级<br>
  
使用方法：这个多层分级是在插入圆点符的基础上再加一个Tab实现的，并且以此类推
### 代码段
```php
<?php
$sql = "insert into tab(name,pwd) values('123','456')";//增
$sql = "delete from tab where id=1";//删
$sql = "update tab set name=456,pwd=123 where id=1";//改
$sql = "select * from tab where id=1";//查
```
```java
public static void main(String[] args)//java主方法
```
```html
<!--html-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>readme-skills</title>
</head>
<body>
  <p>demo</p>
</body>
</html>
```
```python
#python写法
from urllib import request
a=request.urlopen("http://www.baidu.com")
print(a.read().decode('utf-8'))
```
使用方法：在头部和尾部同时加```，并且在头部```的后面加上使用的语言，这样就可以实现语言的高亮，同理这里的```是Tab键上面的，而不是单引号
