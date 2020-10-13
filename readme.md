## HTML入门笔记1

    HTML：超文本标记语言
    发明人：李爵士

## html起手式

    <!DOCTYPE html> 文档类型
    <html zh="CN">  语言：中文；lang="en"为英文
    <head>
    <meta charset="UTF-8"> 文件的字符编码，支持人类所有语言
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 禁用缩放，兼容手机
    <meta http-equiv="X-UA-Compatible" content="ie=edge"> 告诉IE使用最新内核
    <title>我的网页</title> 标题
    </head>
    <body>
    </body>
    </html>

## 常用章节标签

    h1~h6     标题
    section   章节
    article   文章
    p         段落
    header    头部
    footer    脚部
    main      主要内容
    aside     旁支内容
    div       划分     
    
## 全局属性

    class
    contenteditable 使用户能在页面编辑
    hidden 隐藏
    id
    style
    tabindex 键盘（tab）操作访问 注：tabindex="正数"按顺序访问；等于"零"最后访问;等于"-1"别访问我
    title

## 常用内容标签

    ol+li ordered list 有序列表
    ul+li unordered list 无序列表
    dl+dt+dd description list 描述列表
                         term 描述一个对象（术语）
                         data 数据
    pre 用于保留回车、空格
    code 让所有字符等宽
    hr 水平分隔线
    br 换行
    a 超链接； target="_blank" 在新窗口打开
    em 表语气上的强调
    strong 表内容本身的重要性
    quote 行内引用（效果不明显）
    blockquote 块引用（换行引用）