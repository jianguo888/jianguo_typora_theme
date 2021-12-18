# 坚果的typora主题



---

> 做这个主题是受到了庆哥的一篇文章的刺激。
>
> 文章链接https://mp.weixin.qq.com/s/2AYLIFfa-_cIF2EER5emhg




___

## 获取方式

> 如果GitHub图片加载不出来，可以去公众号“坚果前端”，回复typora主题
> 
>哔哩哔哩查看，
> 我的哔哩哔哩主页https://space.bilibili.com/480883651
>
> 

这是我写的一个Typora主题，也是借鉴了`嘉然 `  主题，在这儿要感谢庆哥和作者，

## 使用方法

1. 在GitHub下载此主题，嫌弃速度慢的话，可以在我公众号后台私信我。
2. 打开Typora主题文件夹，点开下载的`jg.css`和`jg2.css`两个文件
3. 重启Typora 将主题切换为`jg`

![image-20211218160822404](https://luckly007.oss-cn-beijing.aliyuncs.com/images/image-20211218160822404.png)

## 前言

typora相信大家都用过，很多人习惯了typora默认的github主题，但我今天看到一个主题。说实话激起了我要设计自己的一款主题的欲望。就有了今天的这个主题。


以下是实际笔记效果：

![image-20211218165354056](https://luckly007.oss-cn-beijing.aliyuncs.com/images/image-20211218165354056.png)





## 字体

首先因为我感觉字体有点小，就把正文换成了17号字体。

```css
html {
    font-size: 18px;
}
```

然后修改了一下字体（如果是Mac用户的话，可以把下面第二行注释掉，因为自带的苹方字体就很好看）。

```css
body {
    font-family: "Vollkorn", Palatino, Times;
    /* font-family: 'Source Han SerifCN', Georgia, Times, 'SimSun', serif!important; */
    color: var(--mid-13);
}
```

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

五级标题

###### 六级标题

## 标题

我认为标题可以说是整个样式中最重要的一部分，因为正文基本上都差不多。

![image-20211218170354424](https://luckly007.oss-cn-beijing.aliyuncs.com/images/image-20211218170354424.png)

一级标题一般对应一本书中的Chapter，故居中表示。一般来说一个md文档中最好只有一个一级标题，如果有内容包含多个章节的话，则应该拆成多个md文档。

二级标题对应section，因此带着一条长长的横线用来分隔。

三级标题是最常用的小标题subsection，微信中只支持到三级标题，在实际的短篇写作中一般也到此为止了。因此不宜花里胡哨，要做到又显目又低调，又精致又普通（

四五六级标题一般用不到，随便糊弄一下就好了。

## 文本样式

![img](https://pic2.zhimg.com/v2-3b263b633366f0dec168b44877c6880d_r.jpg)

对于行内公式，为了醒目和易于查找修改，我特意调成了蓝色（导出时依然是黑色）。

行间代码块如下：

![image-20211218170613750](https://luckly007.oss-cn-beijing.aliyuncs.com/images/image-20211218170613750.png)

因为中文的`斜体`作用几乎为0，因此我把它改成了「显示红色」的效果。

引用块则是大块的淡红色。

## 列表与表格

![img](https://pic2.zhimg.com/v2-aef79f96d7a55254258f7f39970e2001_r.jpg)

把列表和表格都改成了符合主题的红色（不知道为什么，大部分笔记软件默认主题都是红色，例如Notion）。

最后主题也会开源，大家在我的公众号回复“typora主题”

我将会在收到私信后，发给你

开源地址：

编辑不易，喜欢的话，可以关注一下我公众号。

## 下一个版本预告

下一个版本会出黑夜模式。





