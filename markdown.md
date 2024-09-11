# Markdown简介

Markdown的简单语法构件



## 1. 标题

不同数量的`#`可以完成不同的标题，如下：

# 一级标题
## 二级标题
### 三级标题  



## 2.字体

  斜体、粗体、粗体和斜体，删除线，需要在文字前后加不同的标记符号。如下：

| 符号   | 效果 | 
| :--- | --: | 
| \* |  *斜体* |
| \** |  **粗体**|
| \*** | ***粗体加斜体***|

## 3.列表

无序列表的使用，在符号`-`后加空格使用。如下：

- 无序列表 1
- 无序列表 2
- 无序列表 3

有序列表的使用，在数字及符号`.`后加空格后输入内容，如下：

1. 有序列表 1
2. 有序列表 2
3. 有序列表 3

## 4. 引用

引用的格式是在符号`>`后面书写文字。如下：

> Figure Out What Works and Do It. ——李光耀

## 5. 链接

对于该论述，欢迎读者查阅之前发过的文章，[你是《未来世界的幸存者》么？](https://mp.weixin.qq.com/s/s5IhxV2ooX3JN_X416nidA)
<a id="jump_8"></a>


## 6. 图片

插入图片，格式如下：

![这里写图片描述](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg)



## 7. 代码

如果在一个行内需要引用代码，只要用反引号引起来就好，如下：

Use the `printf()` function.

在需要高亮的代码块的前一行及后一行使用三个反引号，同时**第一行反引号后面表示代码块所使用的语言**，如下：

```java
// FileName: HelloWorld.java
public class HelloWorld {
  // Java 入口程序，程序从此入口
  public static void main(String[] args) {
    System.out.println("Hello,World!"); // 向控制台打印一条语句
  }
}
```

## 8. 数学公式


行内数学公式使用方法，采用$\` 和\`$，例如  $`\sqrt{3x-1}+(1+x)^2`$


---

