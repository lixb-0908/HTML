# HTML(HyperText Markup Language)

## HTML是谁发明的？
李爵士 Tim Berners-Lee

## HTML起手式
* 文档类型：DOCTYPE html
* html标签：lang = "zh-CN"
* head标签：
    * meta：charset 文件字符编码；name+content兼容手机，禁用缩放；http-equiv+content让IE浏览器使用最新内核。
    * title：页面标题
## 章节标签
* h1~h6：不同级别的标题，h1最大。
* section：章的标题
* article：文章
* p：段落划分
* header/footer/main/aside：头部/脚注/主要内容/旁支内容
* div：自己划分

## 全局属性
* class：类选择器，与id区分
* style：样式，标签自己的属性，优先级高于css，可以用js直接操作
* contenteditable：可在页面直接编辑
* hidden：隐藏标签所显示的内容
* id：唯一标识某个标签，但是实际上不唯一也检查不出来
* tabindex：不用鼠标，用tab键就可以选中网页上的元素
* title：鼠标放上去显示什么信息

## 内容标签
* 有序 ol+li ；无序 ul+li
* hr/br：分割线/换行
* dl + dt + dd：描述+对象+具体
* em/strong：强调(斜体)/真正重要(加粗)
* quote/blockquote：行引用/块引用
* pre/code：可以保留空格/代码引用
* a 标签：跳转页面