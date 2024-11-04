
平时用IntelliJ IDEA写代码的时候，你有没有用过这些快捷方式：


输入`main`，会弹出自动补全完整的`main`结构:


![](https://static.didispace.com/images3/8e79e9944e2e85f4fb119423491eb631.png)


输入`sout`，会弹出自动补全完整的`System.out`语句:


![](https://static.didispace.com/images3/6b230f4df684bd209b4ccc5bc259d8e2.png)


那么问题来了：


1. 还有哪些快捷方式？
2. 如何定义自己想要的？


## 初识 Live Templates


该功能来自于IntelliJ IDEA的Live Templates配置，你可以通过菜单进入`Setting`，然后搜索`Live Templates`找到它：


![](https://static.didispace.com/images3/d5f209fca908cf856cbf9d954bec54b2.png)


点开`Java`就能看预定义的模板了：


![](https://static.didispace.com/images3/ca3092eeed7bb073779ff46edaf22b82.png)


不是很多，可以挑你常用的记一下即可。


如果要定义要用的模板，可以点击上面的`+`：


![](https://static.didispace.com/images3/95c0896e4dbc3777c62da5a21b2a9684.png)


选择`Live Tempalte`之后在下面会看到一个编辑框：


![](https://static.didispace.com/images3/7d245d737dfc2040dc3d8d9befcd7b11.png)


根据自己需要填写要创建的快捷模板内容。最后记得保存，就可以成功创建了。


尝试在编码框内输入上面定义的快捷方式：`ddfor`，就可以用到上面定义的模板代码了：


![](https://static.didispace.com/images3/506c4347ea0d6e8bb9d939fcc09cc1bb.png)


## 使用进阶


上面仅介绍了Live Template最基本的使用方式。如果还不能满足你的要求，下面几项提示也许可以帮到你。


**使用分组**


如果对这个功能的需求比较多，需要定义比较多模板，尤其是做基础架构给大家定规范做工具的话，还可以在创建Live Template的时候使用Group来创建一些独立的组来方便管理。


![](https://static.didispace.com/images3/95c0896e4dbc3777c62da5a21b2a9684.png)


**使用参数**


很多时候我们创建模版还会需要一些动态的信息，比如自定义模板注释的时候，需要使用：时间、用户等动态信息。


在Live Template的模板定义中是支持使用参数的，使用`$$`来引用，两个`$`中间放参数名。Live Template提供了一些预定义的参数，同时也支持用户自定义变量。


关于这块使用参数和有哪些预定义参数，读者可以自行查阅官方文档：[Live template variables](https://github.com)


**导入导出**


如果你想使用别人的模板，或者想把自己的模板分享给被人，那么可以使用导入导出功能。


功能位置如下图：


![](https://static.didispace.com/images3/4bcd43a0663c85eb842a8274007a8eb4.png)


然后选择你要导出导入的配置内容里选择Live Templates即可


![](https://static.didispace.com/images3/27e665588aedea09be2dbafc29eefc12.png)


好了，今天的分享就到这里，希望内容对您有用 \_，更多关于IDEA的使用技巧可以收藏[《玩转IDEA专栏》](https://github.com):[蓝猫机场](https://fenfang.org)


