# gov360.github.io
这是markdown格式参考展示


## Markdown简介

> Markdown 是一种轻量级标记语 言，它允许人们使用易读易写的 纯文本格式编写文档，然后转换 成格式丰富的HTML页面。    —— [维基百科](https://zh.wikipedia.org/wiki/Markdown)

正如您在阅读的这份文档
===================
它使用简单的符号标识不同的标
---------------------
> 题，将某些文字标记为**粗体**或者*斜体*，创建一个[链接](http://www.example.com)或一个脚注[^demo]。下面列举了几个高级功能，更多语法请按`Ctrl + /`查看帮助。 

### 代码块
``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```

### 表格  
-------------------------
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |
-------------------------

> **提示：**想了解更多，请查看**流程图**[语法][3]以及**时序图**[语法][4]。






### 复选框

使用 `- [ ]` 和 `- [x]` 语法可以创建复选框，实现 todo-list 等功能。例如：

- [x] 已完成事项
- [x] 待办事项1
- [ ] 待办事项2

- [ ] 注意:  
- [ ] 目前支持尚不完全，  
- [ ] 在笔记中勾选复选框  
- [ ] 所以必须在**完美**中
- [ ] 修改 Markdown 原文
- [ ] 是无效 、不能同步的，
- [ ] 才可生效。下个版本将会全面支持。


## 笔记相关

### 笔记本和标签
**测试**增加了`@(笔记本)[标签A|标签B]`语法, 以选择笔记本和添加标签。 **完成测试**， 输入`(`自动会出现笔记本列表，请从中选择。

### 测试标题
**完美人生**会`@(自动使用)[文档|出现]`的第一个标题作为笔记标题。例如本文，就是第一行的 `欢迎使用`。

>**注意：**目前用户在印象笔记中单方面做的任何修改，马克飞象是无法自动感知和更新的。所以请务必回到马克飞象编辑。



### 离线存储  
## 马克  
飞象使用浏览器离线存储将内容实时保存在本地，不必担心网络断掉或浏览器崩溃。为了节省空间和避免冲突，已同步至印象笔记并且不再修改的笔记将删除部分本地缓存，不过依然可以随时通过`文档管理`打开。

> **注意：**虽然浏览器存储大部分时候都比较可靠，但印象笔记作为专业云存储，更值得信赖。以防万一，**请务必经常及时同步到印象笔记**。

## 编辑器相关
### 设置
> **右侧系统**菜单（快捷键`Ctrl + M`）的`设置`中，提供了界面字体、字号、自定义CSS、vim/emacs 键盘`模式`等高级选项。



## 反馈与建议
- 微博：[@马克飞象](http://weibo.com/u/2788354117)，[@GGock](http://weibo.com/ggock "开发者账号")
- 邮箱：<hustgock@gmail.com>

---------
- 感谢:  
<www.baidu.com>请点击右上角，绑定印象笔记账号，开启全新的记录与分享体验吧。

--------
[^demo]: 这是一个示例脚注。请查阅 [MultiMarkdown 文档](https://github.com/fletcher/MultiMarkdown/wiki/MultiMarkdown-Syntax-Guide#footnotes) 关于脚注的说明。  
**限制：**   
印象笔记的笔记内容使用 [ENML][5] 格式，基于 HTML，但是不支持某些标签和属性，例如id，这就导致`脚注`和`TOC`无法正常点击。


  [1]: http://maxiang.info/client_zh
  [2]: https://chrome.google.com/webstore/detail/kidnkfckhbdkfgbicccmdggmpgogehop
  [3]: http://adrai.github.io/flowchart.js/
  [4]: http://bramp.github.io/js-sequence-diagrams/
  [5]: https://dev.yinxiang.com/doc/articles/enml.php

