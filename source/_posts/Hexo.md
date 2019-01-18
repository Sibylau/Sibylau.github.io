---
title: Hexo
---
为了让这里尽快变得温馨起来，这篇整理了Hexo不方便之处的解决办法

Hexo官网 [Hexo](https://hexo.io/) / [documentation](https://hexo.io/docs/) / [troubleshooting](https://hexo.io/docs/troubleshooting.html) /[GitHub](https://github.com/hexojs/hexo/issues).

### Basics

```bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

```bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

Generate static files:

```bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

```bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

发布流程：

```
hexo clean
hexo d -g
```

### Manage my pictures

在每次hexo n的时候自动生成文件夹。

`_config.yml`中`post_asset_folder: true`

### Hexo 迁移

安装Travis-CI



### Markdown

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

```markdown
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~
```

```markdown
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
```

```markdown
分割线们：
---
----
***
*****
```

```markdown
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

```markdown
[超链接名](超链接地址 "超链接title")
title可加可不加
```

```markdown
- 列表内容
+ 列表内容
* 列表内容
1. 列表内容
注意：- + * 跟内容之间都要有一个空格
列表嵌套：上一级和下一级之间敲三个空格即可
```

```markdown
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```

```markdown
单行代码：
`代码内容`
代码块：
(```)
  代码...
  代码...
  代码...
(```)
```

~~~markdown
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
~~~

For more info: https://www.appinn.com/markdown/

