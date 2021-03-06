# Markdown

- 基本语法

  - 标题

    - \#  H1

    - \##  H2

    - \###  H3

    - \####  H4

    - \#####  H5

    - \######  H6

    - 一级标题===

    - 二级标题---

  - 斜体
    - 使用两个“”将要格式的字体包起来，前后都有。也可以使用，但是不建议使用_。

  - 加粗
    - 使用两个“*”将要格式化的字体包起来。

  - 加粗倾斜
    - 三个*号包起来，前后各三个*号。

  - 删除线
    - 前后各两个~~号

  - 分割线
    - 使用四个中划线----，并且使用分割线之前必须有一行空行。

  - 引用
    - 使用>text的格式进行引用，并且在引用之前必须有一行是空行。

  - 列表

    - 列表使用前必须要加空格

    - 无序列表
      - 使用 -、+、*加上文字 text 的格式

    - 有序列表
      - 使用 num.text 的格式

  - 表格

    - 表格前必须空一行

    - 单元格使用 | 进行分割，表头的分割符使用 - 进行分割。

    - \- 和 :- 表示表头和单元格左对齐，-: 表示右对齐，:-: 表示居中对齐。

  - 代码块

    - 行内代码，使用前后一个` 符号包裹起来，注意这里不是单引号是，是反斜号。

    - 多行代码，使用前后三个```符号包裹起来。并可以指定一种编程语言进行高亮显示。

      - 例如```js

      - 你好

      - \```

  - 转义字符
    - 使用反斜杠，\ 进行特殊字符的转义。

  - 链接
    - [title](URL)，例如百度点[这里](http://www.baidu.com/)，注意这里括号之间没有空格。

  - 图片
    - ![title](URL)，这里的 title 指的是图片的替代文字，URL 是图片的地址。

- 注意事项

  - 空格

    - 中英文之间需要增加空格。

    - 中文与数字之间需要增加空格。

    - 数字与单位之间无需增加空格。

    - 全角标点与其他字符之间不加空格。例外：裸链接后面需空格，不能紧跟标点，否则有些渲染器会把标点当成链接的一部分。

    - 中文与链接、强调、行内代码等格式间是否加空格取决于内容（即以上规则），比如书写 Markdown 的规范需要加，而书写中文的规范不需要加。

- 怎么写 Markdown

  - 文件名全部用英文，camelCase。

  - 内容全部用中文写。

  - 图片放到文档所在目录的 images/ 子目录内，使用相对路径引用，比如 ![demo](./images/demo.png)。

  - 引用同一类目下的文档用相对路径，否则用绝对路径，比如 portal 文档引用 mairpc 文档，应使用 /mairpc/xxx 形式的绝对路径。

  - FAQ 子标题应使用疑问句，问号结尾。

  - 引用人名一律用 @xxx.xxx 的形式。

  - 在书写代码块时，请参考 [Prism 支持的语言](https://prismjs.com/#supported-languages)，否则编译时会出现 'Language does not exist xxx'，下面列举了常见的错误写法和对应的正确写法

  - 错误写法正确写法

  - txt, url	text

  - golang    go