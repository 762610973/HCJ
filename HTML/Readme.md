# HTML 简单笔记
- 标签：单标签、双标签
- 双标签关系：包含关系、并列关系

```html
<html> 根标签
    <head>文档头部
    <title></title>
    </head>
    <body>主题内容
    </body>
</html>

以下是初始的文件模板，暂做保存

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>#[[$Title$]]#</title>
</head>
<body>
#[[$END$]]#
</body>
</html>


```
- 属性标签不分先后，属性和属性之间以空格分开
- 属性采用键值对的格式
- 表格table主要是用于显示、展示数据
- thead和tbody：表结构标签，使结构清晰，语义明确
- 列表是用来布局的：列表最大的特点是整齐、有序、整洁
  - 无序列表ul
  - 有序列表ol
  - 自定义列表dl
- form表单：收集用户信息
  - 表单域:action,method,name
  - 表单控件（表单元素）:input输入表单元素、select下拉表单元素、textarea文本域元素
  - 提示信息
- label标签：用于绑定一个表单元素，当点击label标签内的文本时，浏览器会自动将焦点（光标）转到或者选择对应的表单元素上来，用于增加用户体验
- 