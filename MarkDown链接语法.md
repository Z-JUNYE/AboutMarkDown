# MarkDown链接语法
链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。  
超链接MarkDown语法代码：

    [超链接显示名](超链接地址"超链接title")

`MarkDown语法`  

    谷歌网址[Goole Homepage](http://google.com)

谷歌网址[Goole Homepage](http://google.com)

***
## 给链接添加Title
链接Title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分隔。  

    谷歌网址[Google Homepage](http://google.com"谷歌的网址")  

谷歌网址[Google Homepage](http://google.com"谷歌的网址")  

## 网址和Email地址
使用尖括号可以把URL或者email地址变成可点击的链接。  

    <https://google.com>
    <scarzjy@gmail.com>

<https://google.com>
<scarzjy@gmail.com>

## 带格式化的链接
强调链接，在链接语法前后增加星号。要将链接表示为代码，需在方括号中添加反引号。  

    I love supporting the **[EFF](https://eff.org)** 
    This is the *[Google Homepage](https://google.com)*  
    See the section on [`code`](#code)  

I love supporting the **[EFF](https://eff.org)** 
This is the *[Google Homepage](https://google.com)*  
See the section on [`code`](#code) 

## 引用类型链接
引用样式链接是一种特殊的链接，它使URL在MarkDown中更易于显示和阅读。 参考样式链接分为两个部分: 与文本保持内联的部分以及存储在文件中其他位置的部分，以使文本易于阅读。  

### 链接的第一部分格式
引用类型的链接的第一部分使用两组括号进行格式设置。  
第一组方括号包围应显示为链接的文本。  
第二组括号显示了一个标签，该标签用于指向存储在文档其他位置的链接。  

可以在第一组和第二组括号之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。  

