## a标签
* href：跳转到哪里。可以加网址或服务器中的html页面(外部页面)，js代码(伪协议)，特定id会跳转到网页相应标签(内部的锚点)，以及邮件和电话。
* target：_blank在空白页面打开，_self在自己页面打开。_top和_parent，区别主要在于a标签所在的iframe页面。还可以指定特定id的页面(iframe或者新窗口)。
## iframe标签
* 现在很少用，主要用于帮助a标签的理解。
## table标签
* 组成：thead + tbody + tfoot  其中每一行都是tr + td 组合，表头可以用tr + th 表示加粗。
* table-layout：是否自动调整
* border-collapse/border-spacing：是否合并/不合并时的间距
## img标签
* 会发出一个get请求
* src：图片文件
* alt：如果不能正常加载，用什么代替。
* width/height：一个定了另一个就跟着定了，不会变形。
* onload/onerror：看一看是否成功，不成功采取什么措施，如代替展现另一张图片。
* 响应式：在css里加入img{max-width:100%}可以使图片随页面大小而自适应。
## form标签
* 发出get/post请求(method控制)
* action：提交到哪个页面
* target：提交后刷新的页面在哪里打开
* autocomplete：是否提示内容
* type：默认submit，可以提交，如果是button就无法提交。
## input标签
* 让用户输入内容
* type：输入类型很多，如submit/checkbox/file等。
* name：如多选时，怎样知道哪几个选项属于同一个多选题？加name属性。
## 感想
标签属性真是太多了，也不知道自己用的时候能否找到需要的属性。希望自己做项目的时候慢慢体会如何增强工程能力。