# sass的相关知识点

- compass 是开源的css的框架

- sass 是css3的扩展

- compoass 在sass的基础上封装了一系列方法，补充sass

> 使用变量


> 自动转换RGBA的颜色值


> 忘记浏览器的前缀


> 嵌套规则


> media query 更简单


> 自动压缩css

# sass 编译

> sass demo.scss css/demo.css

> sass --watch demo.scss:css/demo.css

> 注释不能用中文，会报错,安装文件的sass的engine.rb Encoding find("utf-8")即可

> //不会编译 /**/会出现在编译的文件中

> compass watch  /compass watch --enviroment production

> compass watch --force 压缩css /*! */压缩也会出现在编译的文件中